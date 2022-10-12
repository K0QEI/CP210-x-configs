# ft991-and-A-varient
using rigcrtld and cqrlog

To force a USB Port to be accessible by a port number usuable by CQRLOG.  The port number you use in your single line command may vary as your radio may not be hooked up to ttyUSB0.  you will have to look over rigctrl documentation to radio number.  you will also need to know your radio serial speed as part of the line.

settings for cqrlog will be as follows
Rig Model: 1 Hamlib Dummuy  reason,  you are already using rigctld (hamlib) to execute commands for the radio
Devbice: 127.0.0.1 reason,  your told rigctld to use port 453x
Port Number: 453x reason, this number may vary as to how many radios you have connected to your comptuer typical is 4532 for radio 1, 4533 for radio 2 and so on,  i use 4534 since i have 3 radios hooked up to my comptuer.  you dont need to do serial speed since the rigctld command has a speed in that line.

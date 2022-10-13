# ft991-and-A-varient
using rigcrtld and cqrlog
this is changable to any radio using the cp210(x) ports

To force a USB Port to be accessible by a port number usuable by CQRLOG.  The port number you use in your single line command may vary as your radio may not be hooked up to ttyUSB0.  you will have to look over rigctrl documentation to radio number.  you will also need to know your radio serial speed as part of the line. the line given is specific to my radio cat speed and what port i need it to talk to.

settings for cqrlog will be as follows

Rig Model: 135  
Devbice: 127.0.0.1:453x reason,  your told rigctld to use 453x 
Port Number: 1453x reason, this number may vary as to how many radios you have connected to your comptuer typical is 4532 for radio 1, 4533 for radio 2 and so on,  i use 4534 since i have 3 radios hooked up to my comptuer.  you dont need to do serial speed since the rigctld command has a speed in that line.

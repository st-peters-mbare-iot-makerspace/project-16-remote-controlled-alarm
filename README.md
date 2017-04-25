# project-16-remote-controlled-alarm
IMPORTANT

1. We didnt use the default Arduino library but the Newtone library found here https://bitbucket.org/teckel12/arduino-new-tone/wiki/Home#!download-install

2. For electronic schematics we combined Project 6 and Project 14.

Known Error:
arduino-1.8.2/libraries/RobotIRremote/src/IRremoteTools.cpp:5:16: error: 'TKD2' was not declared in this scope
 int RECV_PIN = TKD2; // the pin the IR receiver is connected to
                ^
Solution:
1. Remove the RobotIRremote library from Arduino
2. Download and install the Arduino IRRemote library found here: https://github.com/z3t0/Arduino-IRremote





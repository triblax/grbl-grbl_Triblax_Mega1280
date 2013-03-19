fork of base Grbl/grbl - this version: Grbl v0.8c Atmega1280 16mhz 9600baud

#Grbl - An embedded g-code interpreter and motion-controller for the Arduino/AVR328 microcontroller
------------

Grbl is a no-compromise, high performance, low cost alternative to parallel-port-based motion control for CNC milling. It will run on a vanilla Arduino (Duemillanove/Uno) as long as it sports an Atmega 328. 

The controller is written in highly optimized C utilizing every clever feature of the AVR-chips to achieve precise timing and asynchronous operation. It is able to m	aintain more than 30kHz of stable, jitter free control pulses.

It accepts standards-compliant G-code and has been tested with the output of several CAM tools with no problems. Arcs, circles and helical motion are fully supported, as well as, other basic functional g-code commands. Functions and variables are not currently supported, but may be included in future releases in a form of a pre-processor.

Grbl includes full acceleration management with look ahead. That means the controller will look up to 18 motions into the future and plan its velocities ahead to deliver smooth acceleration and jerk-free cornering.

_The project was initially inspired by the Arduino GCode Interpreter by Mike Ellery_

# SmartAnimalTraps is still in process 06.2022!!!
Electrical non-deadly animal traps built up with intelligent radio module, drive electronics for servomotors
(flapdrive) and drive electronics for different low power light barriers.

Intelligent radio module:

Wireless module receives and evaluates the data received from a transmitter.

In order to carry out a command from a transmitter, it must first be taught.
Teaching of a transmitter is carried out very easily by means of a button.
As required, up to 60 transmitters can be taught with all keys or individual transmission keys.
The particular highlight is the feedback from the receiver. You can see from the transmitter
whether the wireless communication was successful and receive information about the quality of the transmission path.

Long range, tested over a distance of 150 meters

Examples after teaching the modules:
 
Hand-held transmitter1 /Key1 /Trap1 /Shutter open

Hand-held transmitter1 /Key2 /Trap1 /Shutter closed

Hand-held transmitter1 /Key3 /Trap2 /Shutter open

Hand-held transmitter1 /Key4 /Trap2 /Shutter closed


Hand-held transmitter1 /Key1 /Trap1/Trap2/Trap3/Trap4 /Shutter open

Hand-held transmitter1 /Key2 /Trap1/Trap2/Trap3/Trap4 /Shutter closed



Drive electronics for servomotor and flap:

Trigger always the same postions over inputs signals (two end points) or over pushbuttons.

The servo setup procedure consists of 4 steps:

Adjust end position 1. This can be the most left or the most right end point. This position will be reached after power-up if valid servo data has been found in FLASH.
Adjust end position 2. This is the opposite end position to position 1.
Adjust servo speed. The servo permanently moves between the two end points. The speed can be adjusted via S1 and S2.
Asserting S3 the 4th time stores the servo parameters into FLASH and returns to normal operation

Examples for shutter after adjust the end positions:

Input Signal1 end position 1/ Shutter open
Input Signal2 end position 2/ Shutter closed

Pushbutton1 end position 1/ Shutter open
Pushbutton2 end position 2/ Shutter closed


Drive electronics for light barries:

Supported two low power light barriers, adjustable for different distances(size of animal). 10cm to 3.3meter
Scattered light independently and invisible.

Examples for light barriers:
If both light barriers are triggered the Shutter will be closed.




3_RadioModule_V1.5_&_Servo_modified
- full rotation of motor (rotated 360°)
- no light barries

Current consumption:  
Standby 30mA@9V with LED
Clocking after 10 minutes.
Standby 11.5mA@9V with LED

Motor is steady turning 188mA@9V

https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/31_RadioModule_V1.5_Servomodified.JPG


2_RadioModule_V2.0_&_Electronics_Servo
- Servomotor and Shutter is adjusted to the end positions.
- no light barries

Current consumption:  

Standby 20.5mA@9V with LED
Clocking after 10 minutes.
Standby 2.2mA@9V

https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/21_Anschluss_1.JPG
https://github.com/peterloes/Servo_Engine

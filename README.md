# SmartAnimalTraps
Electrical non-deadly animal traps built up with intelligent radio module, drive electronics for servomotors
(flapdrive) and drive electronics for different low power light barriers.

Author: Loës P. (2022)



## Intelligent radio module:

Wireless module receives and evaluates the data received from a transmitter.

In order to carry out a command from a transmitter, it must first be taught.
Teaching of a transmitter is carried out very easily by means of a button.
As required, up to 60 transmitters can be taught with all keys or individual transmission keys.
The particular highlight is the feedback from the receiver. You can see from the transmitter
whether the wireless communication was successful and receive information about the quality of the transmission path.
Long range tested over a distance of 150 meters.

Examples after teaching the modules:
 
Hand-held transmitter1 /Key1 /Trap1 /Shutter open

Hand-held transmitter1 /Key2 /Trap1 /Shutter closed

Hand-held transmitter1 /Key3 /Trap2 /Shutter open

Hand-held transmitter1 /Key4 /Trap2 /Shutter closed
 
or 
 
Hand-held transmitter1 /Key1 /Trap1/Trap2/Trap3/Trap4 /Shutter open

Hand-held transmitter1 /Key2 /Trap1/Trap2/Trap3/Trap4 /Shutter closed


## Drive electronics for servomotor and flap:

Trigger always the same postions over input signals (two end points) or over pushbuttons.

The servo setup procedure consists of 4 steps:

Adjust end position 1. This can be the most left or the most right end point. This position will be reached after power-up if valid servo data has been found in FLASH.
Adjust end position 2. This is the opposite end position to position 1.
Adjust servo speed. The servo permanently moves between the two end points. The speed can be adjusted via S1 and S2.
Asserting S3 the 4th time stores the servo parameters into FLASH and returns to normal operation

Examples for Shutterposition after adjust the end positions:

Input Signal1 end position 1/ Shutter open

Input Signal2 end position 2/ Shutter closed

or 

Pushbutton1 end position 1/ Shutter open

Pushbutton2 end position 2/ Shutter closed


## Drive electronics for light barries:

Supported two low power light barriers, adjustable for different distances(size of animal). 10cm to tested 3.3meter
Scattered light independently and invisible.

Examples for light barriers:
If both light barriers are triggered the Shutter will be closed.


#### 1_RadioModule_&_ElectronicsLightBarriers_&_ElectronicsServo 
- Radio Module 
- Electronic Lightbarrier for different distances.
- Servomotor and Shutter is adjusted to the end positions.

Current consumption: // In process DD.06.2022!!!

https://github.com/peterloes/Light_Barrier

https://github.com/peterloes/Servo_Engine

--> Protection against misuse!!! Dear follower, please contact me via email to get more information about the used wireless radio module. 

#### 2_RadioModule_V2.0_&_ElectronicsServo
- Radio Module
- Electronics Radio Module V2.0
- No light barries
- Servomotor and Shutter is adjusted to the end positions.
- Protection against misuse. Dear follower, please contact me via email to get more information about the used wireless radio module. 

Current consumption:  

Standby 20.5mA@9V with LED
Clocking after 10 minutes.
Standby 2.2mA@9V

https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/21_Anschluss_1.JPG

https://github.com/peterloes/Servo_Engine

--> Protection against misuse!!! Dear follower, please contact me via email to get more information about the used wireless radio module. 


#### 3_RadioModule_V1.5_&_ServoModified
- Radio Module
- Electronics Radio Module V1.5
- No light barries
- Full rotation of modified Servomotor --> Motor rotated 360°

![My image](https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/31_RadioModuleV1.5_ServoModified.JPG)

Current consumption:  
Standby 30mA@9V with LED
Clocking after 10 minutes.
Standby 11.5mA@9V with LED

Motor is steady turning 188mA@9V

https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/31_RadioModule_V1.5_Servomodified.JPG

--> Protection against misuse!!! Dear follower, please contact me via email to get more information about the used wireless radio module. 


#### 4_ReusedFrontplateLightBarriers_&_ElectronicsServo
- Radio Module
- Reused frontplate nestbox with Lightbarriers
- Servomotor and Shutter is adjusted to the end positions.

Current consumption needed 500mA@9V for Servomotor!

Smart Nestbox Frontplatte reuse 3.3V to max. 6V and LightBarrier circuit board 3.3V to max.60V 

Two high level Signal: 105µA@3,3V  -- Two low  level Signal: 1,47mA@3,3V

Two high level Signal: 100µA@5V    -- Two low  level Signal: 160µA@5V

Two high level Signal: 100µA@13,2V -- Two low  level Signal: 1,45mA@13,2V

https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/4_ElectronicsServo_LightBarrier.JPG

https://github.com/peterloes/Servo_Engine

--> Protection against misuse!!! Dear follower, please contact me via email to get more information about the used wireless radio module. 


#### 5_ElectronicsLightBarriers_&_ElectronicsServo_2022
- No radio module
- Electronic Lightbarriers are switching Shutterpositions.
- Servomotor and Shutter is adjusted to the end positions.

![My image](https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/5_ElectronicsLightBarrier_ElectronicsServo.jpg)

Current consumption needed 500mA@9V for Servomotor!

Electronic for LightBarrier ..@9V

Electronic Servomotor and Electronic LightBarrier

With two lightbarrier high level Signal: 204µA@9V -- Two lightbarrier low level Signal : 1.65mA@9V

Receiver Vishay "TSSP58038" and LED Vishay "VSLB3940" and LightBarrier circuit board 3.3V to max.60V 


https://github.com/peterloes/Light_Barrier

https://github.com/peterloes/Servo_Engine


#### 6_ReusedFrontplateLightBarriers_&_ElectronicsServo
- No Radio Module
- Reused frontplate from nestbox with Lightbarriers are switching Shutterpositions.
- Servomotor and Shutter is adjusted to the end positions.

Current consumption needed 500mA@9V for Servomotor!

Smart Nestbox Frontplatte reuse 3.3V to max. 6V and LightBarrier circuit board 3.3V to max.60V 

Two high level Signal: 105µA@3,3V  -- Two low  level Signal: 1,47mA@3,3V

Two high level Signal: 100µA@5V    -- Two low  level Signal: 160µA@5V

Two high level Signal: 100µA@13,2V -- Two low  level Signal: 1,45mA@13,2V

https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/4_ElectronicsServo_LightBarrier.JPG

https://github.com/peterloes/Servo_Engine

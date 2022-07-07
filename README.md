# SmartAnimalTraps
Electrical applications for non-deadly animal traps built up with intelligent radio module, drive electronics for servomotors
(flapdrive) and drive electronics for different low power lightbarriers.

Author: Loës P. (2022)



#### Intelligent radio module:

Wireless module receives and evaluates the data received from a transmitter.

In order to carry out a command from a transmitter, it must first be taught.
Teaching of a transmitter is carried out very easily by means of a button.
As required, up to 60 transmitters can be taught with all keys or individual transmission keys.
The particular highlight is the feedback from the receiver. You can see from the transmitter
whether the wireless communication was successful and receive information about the quality of the transmission path.

Examples after teaching the modules:
 
Hand-held transmitter1-->Key1 --Trap1-->Shutter open__ Hand-held transmitter1-->Key2 --Trap1-->Shutter closed

Hand-held transmitter1-->Key3 --Trap2-->Shutter open__ Hand-held transmitter1-->Key4 --Trap2-->Shutter closed

or 
 
Hand-held transmitter2 --> Key1 -- Trap1-Trap2-Trap3-Trap4 --> Shutter open

Hand-held transmitter2 --> Key2 -- Trap1-Trap2-Trap3-Trap4 --> Shutter closed


#### Drive electronics for servomotor and flap:

Trigger always the same positions over input signals (two end points) or over pushbuttons.

The servo setup procedure consists of 4 steps:

Adjust end position 1. This can be the most left or the most right end point. This position will be reached after power-up if valid servo data has been found in FLASH.
Adjust end position 2. This is the opposite end position to position 1.
Adjust servo speed. The servo permanently moves between the two end points. The speed can be adjusted via S1 and S2.
Asserting S3 the 4th time stores the servo parameters into FLASH and returns to normal operation

Examples for shutterposition after adjust the end positions:

Input signal1 end position 1 --> Shutter open_____ Input signal2 end position 2 --> Shutter closed

or 

Pushbutton1 end position 1   --> Shutter open_____ Pushbutton2 end position 2   --> Shutter closed


#### Drive electronics for light barries:

Supported two low power lightbarriers, adjustable for different distances(size of animal) 10centimetres to tested 3.3metres. 
The beam is scattered light independently and invisible.
Wide power input range of lightbarrier circuit board 3.3V to max.60V. Used receiver from Vishay "TSSP58038" and LED from Vishay "VSLB3940".


Examples for lightbarriers:

Lightbarrier 1 and lightbarrier 2 can connected with logic AND. Both lightbarriers needs then a falling edge to 0V to close the shutter.


## 1 RadiomoduleV1.0 & electronicsLightbarriers & electronicsServo
- Radio module V1.0 add-on board 
- Electronic lightbarriers for different distances.
- Servomotor and shutter is adjusted to the end positions.

!!! Packaging in process DD.07.2022 !!!

![My image](https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/11_overview.JPG)

The radio handheld transmitter is able to open and close the shutter, from a distance tested over 100 metres.

Lightbarrier 1 and lightbarrier 2 are connected with logic AND. Both lightbarriers needs then a falling edge to 0V to close the shutter.

Lightbarrier 1 and lightbarrier 2 is forbidden to open the Shutter.

Pushbutton 1 and pushbutton 2, mounted on the top of the electronical circuit, are able to open and close the shutter.

### Current consumption:

Standby 20.8mA@9V with LEDs.

Sleep mode 2.3mA@9V delay after 10 minutes.

https://github.com/peterloes/SmartAnimalTraps/blob/main/Schematics/radio_module_V1.0.brd.pdf

https://github.com/peterloes/Light_Barrier

https://github.com/peterloes/Servo_Engine

--> Protection against misuse!!! Dear follower, please contact me via email to get more information about the used wireless radio module. 


## 2 RadiomoduleV2.0 & electronicsServo
- Radio module V2.0 add-on board
- No lightbarries
- Servomotor and shutter is adjusted to the end positions.

!!! Packaging in process DD.07.2022 !!!

![My image](https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/21_Anschluss_1.JPG)

The radio handheld transmitter is able to open and close the shutter, from a distance tested over 100 metres.

Pushbutton 1 and pushbutton 2, mounted on the top of the electronical circuit, are able to open and close the shutter.


### Current consumption:  

Standby 20.5mA@9V with LEDs

Sleep mode 2.2mA@9V delay after 10 minutes.

https://github.com/peterloes/SmartAnimalTraps/blob/main/Schematics/radio_module_V2.0.brd.pdf

https://github.com/peterloes/Servo_Engine

--> Protection against misuse!!! Dear follower, please contact me via email to get more information about the used wireless radio module. 


## 3 RadiomoduleV3.0 & modifiedServo
- Radio module V3.0 add-on board
- No lightbarries
- Full rotation of modified servomotor --> Motor rotation 360°

![My image](https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/31_RadioModuleV1.5_ServoModified.JPG)

The radio handheld transmitter is able to open, close and to rotates the shutter, from a distance tested over 100 metres.


### Current consumption:  

Standby      30mA@9V with LEDs

Sleep mode 11.5mA@9V delay after 10 minutes.

Motor is steady turning 188mA@9V


https://github.com/peterloes/SmartAnimalTraps/blob/main/Schematics/radio_module_V3.0.brd.pdf

https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/33_Servo_modified.JPG

--> Protection against misuse!!! Dear follower, please contact me via email to get more information about the used wireless radio module. 


## 4 ReusedFrontplateLightBarriers & electronicsServo
- Radio module
- Reused frontplate nestbox with lightbarriers
- Servomotor and shutter is adjusted to the end positions.

!!! Electronics Radio Module V??? and packaging in process DD.07.2022 !!!

### Current consumption needed 500mA@9V for Servomotor:

Smart nestbox frontplatte reuse 3.3V to max. 6V and lightbarrier circuit board 3.3V to max.60V 

Two high level signals: 105µA@3,3V  -- Two low level signals: 1,47mA@3,3V

Two high level signals: 100µA@5V    -- Two low level signals:  160µA@5V

Two high level signals: 100µA@13,2V -- Two low level signals: 1,45mA@13,2V

LINK!!! Electronics Radio Module V?? // In process DD.06.2022!!!

https://github.com/peterloes/Servo_Engine

--> Protection against misuse!!! Dear follower, please contact me via email to get more information about the used wireless radio module. 


## 5 electronicsLightBarriers & electronicsServo
- No radio module
- Electronic lightbarriers are switching shutterpositions.
- Servomotor and shutter is adjusted to the end positions.

![My image](https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/5_ElectronicsLightBarrier_ElectronicsServo.jpg)

Lightbarrier 1 and lightbarrier 2 are able to open and close the shutter.

Lightbarrier 1 and lightbarrier 2 are connected with logic AND. Both lightbarriers needs then a falling edge to 0V to close the shutter.

Lightbarrier 1 and lightbarrier 2 is forbidden to open the Shutter.

Pushbutton 1 and pushbutton 2, mounted on the top of the electronical circuit, are able to open and close the shutter.

### Current consumption needed 500mA@9V for Servomotor:

Electronic servomotor and electronic lightbarriers

Two lightbarriers high level signals: 204µA@9V --- Two lightbarriers low level signals : 1.65mA@9V

https://github.com/peterloes/Light_Barrier

https://github.com/peterloes/Servo_Engine


## 6 ReusedFrontplateLightBarriers & electronicsServo
- No Radio module
- Reused frontplate from nestbox with lightbarriers are switching shutterpositions.
- Servomotor and shutter is adjusted to the end positions.

![My image](https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/6_ReusedFrontplateLightBarriers_ElectronicsServo.JPG)

Lightbarrier 1 and lightbarrier 2 are able to open and close the shutter.

Lightbarrier 1 and lightbarrier 2 are connected with logic AND. Both lightbarriers needs then a falling edge to 0V to close the shutter.

Lightbarrier 1 and lightbarrier 2 is forbidden to open the Shutter.

Pushbutton 1 and pushbutton 2, mounted on the top of the electronical circuit, are able to open and close the shutter.


### Current consumption needed 500mA@9V for Servomotor:

Smart nestbox frontplatte reused 3.3V to max. 6V and lightbarrier circuit board 3.3V to max.60V 

!!! repeat measurements DD.06.2022

Two high level signal: 105µA@3,3V  -- Two low level signal: 1,47mA@3,3V

Two high level signal: 100µA@5V    -- Two low level signal: 160µA@5V

Two high level signal: 100µA@13,2V -- Two low level signal: 1,45mA@13,2V


https://github.com/peterloes/Servo_Engine



### EXTENSIONS

https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/SailwinchServo.jpg

https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/Snaptrap.jpg

https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/LightBarrier_example.jpg

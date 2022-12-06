# SmartAnimalTraps
Electrical applications for non-deadly animal traps built up with intelligent radio module, drive electronics for servomotors
(flap drive) and drive electronics for different low power light barriers.

Author: Loës P. (2022) [![DOI](https://zenodo.org/badge/502934599.svg)](https://zenodo.org/badge/latestdoi/502934599)



#### Intelligent radio module:

Wireless module receives and evaluates the data received from a transmitter.

In order to carry out a command from a transmitter, it must first be taught.
Teaching of a transmitter is carried out very easily by means of a button.
As required, up to 60 transmitters can be taught with all keys or individual transmission keys.
The particular highlight is the feedback from the receiver. You can see from the transmitter
whether the wireless communication was successful and receive information about the quality of the transmission path.
Electronical release range of 70 metres tested in urban environment. 

https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/13_wireless_radiomodule.JPG

Examples after teaching the modules:
 
Hand-held transmitter --> Button1 -- Trap1 --> Shutter closed

Hand-held transmitter --> Button2 -- Trap1 --> Shutter open

Hand-held transmitter --> Button3 -- Trap2 --> Shutter closed

Hand-held transmitter --> Button4 -- Trap2 --> Shutter open

or 
 
Hand-held transmitter --> Button1 -- Trap1-Trap2-Trap3-Trap4 --> Shutter closed

Hand-held transmitter --> Button2 -- Trap1-Trap2-Trap3-Trap4 --> Shutter open


#### Drive electronics for servomotor and flap:

Trigger always the same positions over input signals (two end points) or over pushbuttons.

The servo setup procedure consists of 4 steps:

Adjust end position 1. This can be the most left or the most right end point. This position will be reached after power-up if valid servo data has been found in FLASH.
Adjust end position 2. This is the opposite end position to position 1.
Adjust servo speed. The servo permanently moves between the two end points. The speed can be adjusted via S1 and S2.
Asserting S3 the 4th time stores the servo parameters into FLASH and returns to normal operation

.https://github.com/peterloes/Servo_Engine

Examples for shutter positions after adjust the end positions:

Pushbutton 1 end position 1 --> Shutter open 

Pushbutton 2 end position 2 --> Shutter closed

or

Input signal 1 end position 1 --> Shutter open

Input signal 2 end position 2 --> Shutter closed

#### Drive electronics for light barriers:

Supported two low power light barriers, adjustable for different distances(size of animal) 10 centimetres to tested 3.3 metres. 
The beam is scattered light independently and invisible.
Wide power input range of light barrier circuit board 3.3V to max.60V. Used receiver from Vishay "TSSP58038" and LED from Vishay "VSLB3940"

https://github.com/peterloes/Light_Barrier

Examples for light barriers:

Light barrier 1 and light barrier 2 are connected with logic AND. Both light barriers needs a falling edge of the signals to close the shutter.

Light barrier 1 or light barrier 2 are able to open or to close the shutter.


## 1 RadiomoduleV1.0 & electronicsLightbarriers & electronicsServo
- Radio module V1.0 add-on board (not illustrated)
- Electronic light barriers for different distances.
- Servomotor and shutter is adjusted to the end positions.

![My image](https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/11_overview.jpg)

The radio handheld transmitter is able to open and close the shutter by pressing a button.

Light barrier 1 and light barrier 2 are connected with logic AND. Both light barriers needs a falling edge of the signals to close the shutter. 
Light barrier 1 and light barrier 2 is forbidden to open the shutter.

Pushbutton 1 and pushbutton 2, mounted on the top of the electronical circuit, are able to open and close the shutter.

### Current consumption:

Standby 20.8mA@6V, clocked approx. 2.0mA@6V (after 10 minutes).

Operate mode 320mA@6V (max.)

### Components:

https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/13_wireless_radiomodule.JPG

https://github.com/peterloes/SmartAnimalTraps/blob/main/Schematics/radio_module_V1.0.brd.pdf

https://github.com/peterloes/Light_Barrier

https://github.com/peterloes/Servo_Engine

--> Protection against misuse!!! Dear follower, please contact me via email to get more information about the used wireless radio module. 

!!! Packaging in process DD.07.2022 !!!

## 2 RadiomoduleV2.0 & electronicsServo
- Radio module V2.0 add-on board (not illustrated) 
- No light barriers
- Servomotor and shutter is adjusted to the end positions.

![My image](https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/21_overview.JPG)

The radio handheld transmitter is able to open and close the shutter by pressing a button.

Pushbutton 1 and pushbutton 2, mounted on the top of the electronical circuit, are able to open and close the shutter.


### Current consumption:  

Standby 20.5mA@6V, clocked approx. 2.3mA@6V (after 10 minutes).

Operate mode 235mA@6V (max.)

### Components:

https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/13_wireless_radiomodule.JPG

https://github.com/peterloes/SmartAnimalTraps/blob/main/Schematics/radio_module_V2.0.brd.pdf

https://github.com/peterloes/Servo_Engine

--> Protection against misuse!!! Dear follower, please contact me via email to get more information about the used wireless radio module. 

!!! Packaging in process DD.07.2022 !!!

## 3 RadiomoduleV3.0 & modifiedServo
- Radio module V3.0 add-on board (Version from year 2010, to revision)
- No light barriers
- Full rotation of modified servomotor --> Motor rotation 360° --> left/right rotations

![My image](https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/31_overview.JPG)

The radio handheld transmitter is able to open, close and to rotates the shutter by pressing a button.

### Current consumption:  

Standby 30mA@6V, clocked approx. 11.4mA@6V (after 10 minutes). With LEDs.

Operate mode 179mA@6V Motor is steady turning. With LEDs.

### Components:

https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/13_wireless_radiomodule.JPG

https://github.com/peterloes/SmartAnimalTraps/blob/main/Schematics/radio_module_V3.0.brd.pdf

https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/33_Servo_modified.JPG

https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/34_old_batterypack.JPG

--> Protection against misuse!!! Dear follower, please contact me via email to get more information about the used wireless radio module. 


## 4 RadiomoduleV4.0 & reusedFrontplate & electronicsLightbarriers & electronicsServo
- Radio module V4.0 add-on board (not illustrated)
- Reused frontplate from nestbox included light barriers.
- Electronic light barriers.
- Servomotor and shutter is adjusted to the end positions.

![My image](https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/41_overview.JPG)

The radio handheld transmitter is able to open and close the shutter by pressing a button.

Light barrier 1 and light barrier 2 are connected with logic AND. Both light barriers needs a falling edge of the signals to close the shutter.
Light barrier 1 and light barrier 2 is forbidden to open the shutter.

Pushbutton 1 and pushbutton 2, mounted on the top of the electronical circuit, are able to open and close the shutter.


### Current consumption:

Standby 21.9mA@6V, clocked approx. 3.5mA@6V (after 10 minutes). With LEDs.

Operate mode 303mA@6V (max.). With LEDs.

### Components:

https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/13_wireless_radiomodule.JPG

https://github.com/peterloes/SmartAnimalTraps/blob/main/Schematics/radio_module_V4.0.brd.pdf

https://github.com/peterloes/Light_Barrier

https://github.com/peterloes/Servo_Engine

Frontplate nestbox

https://github.com/peterloes/RFID-MS

https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/7_Supplier.txt

--> Protection against misuse!!! Dear follower, please contact me via email to get more information about the used wireless radio module. 

!!! Packaging in process DD.07.2022 !!!

## 5 ElectronicsLightBarriers & electronicsServo
- No radio module
- Electronic light barriers for different distances are switching shutter positions.
- Servomotor and shutter is adjusted to the end positions.

![My image](https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/51_overview.JPG)

Light barrier 1 or light barrier 2 are able to open or to close the shutter.

Pushbutton 1 or pushbutton 2, mounted on the top of the electronical circuit, are able to open or to close the shutter.

### Current consumption:

Standby 0,22mA@6V --> 220µA@6V

Operate mode 322mA@6V (max.)

### Components:

https://github.com/peterloes/Light_Barrier

https://github.com/peterloes/Servo_Engine


## 6 ReusedFrontplate & electronicsServo
- No radio module
- Reused frontplate from nestbox included light barriers. Switching shutter positions.
- Servomotor and shutter is adjusted to the end positions.

![My image](https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/61_overview_1.JPG)

Light barrier 1 or light barrier 2 are able to open or to close the shutter.

Pushbutton 1 or pushbutton 2, mounted on the top of the electronical circuit, are able to open or to close the shutter.

### Current consumption:

Standby 0,05mA@6V --> 50µA@6V

Operate mode 375mA@6V (max.)

### Components:

https://github.com/peterloes/Servo_Engine

Frontplate nestbox

https://github.com/peterloes/RFID-MS

https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/7_Supplier.txt

### EXTENSIONS

https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/SailwinchServo.jpg

https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/Snaptrap.jpg

https://github.com/peterloes/SmartAnimalTraps/blob/main/Getting_Started_Tutorial/LightBarrier_example.jpg 

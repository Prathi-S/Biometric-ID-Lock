# Biometric-ID-Lock
This is a fingerprint lock that uses an Arduino Microcontroller and 4-Channel Relay Module to unlock a solenoid lock. When the uploaded fingerprint is detected, a red light glows and the solenoid lock unlocks. 

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Prathivaradhan Sattiamoorthy | Dublin High School | Mechanical Engineering/Computer Science | 11


___
___


# Materials
-  Arduino
-  4-Channel Relay Module
-  12V Solenoid Lock
-  Fingerprint Scanner
-  Copper Board
-  LCD Display
-  Breadboard
-  12V Battery
-  Led Light (1)
-  Resistor 220 Ohms (1)
-  Jumper Wires (Many)
-  USB Cable
-  Wood Slab
-  Tape
<br>

# First Milestone

**Milestone 1 Video**
<br>
<br>
  [![Milestone 1 Video](https://user-images.githubusercontent.com/110252095/183277001-f124d9a3-5131-4ac8-a013-08fb70ff1737.jpeg)](https://youtu.be/ssd7OVwMDoo "Milestone 1 Video")
<br>
<br>
During my first milestone, I built a fingerprint scanner which uploads the fingerprints as templates and verifies to check matching and displays the message in output if its matched or not. This module has FLASH memory for storing fingerprints, and can be used with any microcontroller or system with a TTL serial interface, and can be added to security systems, door locks, time and attendance systems, and so on. Some of the main components include the Arduino microcontroller and fingerprint scanner. The Arduino microcontroller is the center of the circuit as the code is uploaded and the components which sends and recieves data. The easiest way to control the fingerprint sensor module with Arduino is to use the sensor's Adafruit library. The fingerprint sensor module used in this project has wires of the same color, so it is necessary to distinguish the wire and connect to Arduino board accordingly. <br>
VCC-Red wire - Connect to 5V <br>
RX-Green wire - Pin 2 <br>
TX-White wire - Pin 3 <br>
GND-Black wire - GND <br>
The easiest way to control the fingerprint sensor module with Arduino is to use the sensor's Adafruit library. Connect the fingerprint sensor module to the Arduino. To enroll select the template number and scan your finger, rescan again to make sure its gets stored properly. If the finger module couldn't scan the fingerprint properly due to Image failures or packet receive error it throws the serial output message accordingly. The template number where the fingerprint scan is stored would be given with in the serial output. To verify the fingerprint, run the Fingerprint_verify program to check the fingerprint matches. If the fingerprint matches it gives the template number and gives the output as match found. Sometimes, if your fingers are not placed correctly as they were saved, the sensor can hardly recognize it. Place your finger slowly on the scanner, so that the sensor will work better. 

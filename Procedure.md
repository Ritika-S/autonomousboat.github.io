## **Boat Exterior & Interior**
### __Used: 3D Printed__

The outer structure of the boat was 3D printed, to allow for quick prototyping and changes. Inorder to water proof the boat, 
we used epoxy and tape to glue and hold down the pieces of the boat (epoxy can also be used as a waterproofing agent).

[CAD files](https://www.dropbox.com/sh/irfmggc8k5queg0/AACh7eVSw1JcP0g08k7TlmTpa?dl=0)


## **Receiver to Pixhawk**
### __Used: Futaba R617FS along with PPM encoder__

We used a Futaba R617FS reciever to allow for remote control, but inorder to make it compatible with the PixHawk we added a PPM
encoder. Alternatively here are some pre-determined compatible S.Bus devices: FrSky X8R, FrSky XSR, Futaba R2008SB, 
Futaba R6008SB

<img src="\Images\Screen Shot 2018-06-07 at 1.55.16 PM.png">


## **Receiver to Radio Transmitter**
### __Used: Futaba R617FS and Futaba T7C__

1.	Connect the R617FS to a power source (4.8V or 6.0V battery source), by using pins 7/8

    a.	Keep the Radio Transmitter off

2.	The R617FS LED light should be a red color, indicating the that there is no radio transmitting nearby

3.	Turn on the transmitter (T7C)

4.	The R617FS LED light should be blinking a green light, to indicate that it senses the presence of a transmitter nearby

5.	To pair the transmitter to the receiver take a screwdriver and press the button located between 2 coaxial antenna cables

    a.	Press the button for approximately 2 seconds, during this time the LED light should momentarily turn red

    b.	Once you have stopped pressing the button the LED light should turn to a solid green light, indicating that the radio     transmitter and the receiver are now paired

6.	You can either check that they are paired by using a servo plugged into pin 4, or by measuring the change in electrical signal when we use the transmitter

    a.	Use the oscilloscope to measure the electrical signal between the signal cable of the PPM signal (orange) and a           grounded source 


## **Setting up the PixHawk**
### __Use APM Planner for MacOS and Mission Planner for Windows (Prefered)__

[Physical Installation of PixHawk](http://ardupilot.org/copter/docs/common-pixhawk-wiring-and-quick-start.html) 

[Calibration of the PixHawk](http://ardupilot.org/rover/docs/apmrover-setup.html)

<img src="\Images\Screen Shot 2018-06-07 at 1.55.09 PM.png">

## **Motor to PixHawk**
### __Used: Blue Robotics T100 Thruster, Blue Robotics Basic ESC, OMNIBUS Flight Controller Board__




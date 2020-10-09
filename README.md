# Smart-Transit
Project under Vdart Digital

# Process: 
The current setup for Smart Public transit is to have a GPS Tracking device that sends wifi signals to the internet where it can be displayed on Google Maps API on a Mobile application. By doing this, the citizens of Trichy, India will receive better efficiency managing public transportation.

# Device:
We are going to have a GPS shield/Breakout Board attached to the arduino and use an external GPS antenna to track location data. Furthermore, there will be an on-board SD Card reader to be able to track data or datalog the information from the sensors. This data can be sent via SIM Card/Data towards an application/ through the internet where the second part of this project, a mobile application using Google Maps API can find the location of the vehicle.

# Items/Arduino
* GPS Sensor from adafruit
* Band antenna from adafruit
* SIM card
* Arduino uno
* Lithium Ion polymer battery from adafruit
* SIM card board from adafruit

# Hardware Configurations
* Plug in power configurations
  * Connect the 5V Pin from the arduino to the red power line
  * Connect the GND pin from arduino to the blue power line
* Place the FONA 808/GPS Breakout board onto the breadboard
  * Connect VIO pins to the red power line
  * Connect GND and Key bins to the blue power line
* Configuring the Data connection
  * Connect FONA RST pin to the Arduino pin 4
  * Connect FONA TX pin to Arduino pin 3
  * Connect FONA RX pin to Arduino pin 2
* Connect the other components
  * Connect the Lithium battery, GPS antenna, and GSM antenna to the breakout board

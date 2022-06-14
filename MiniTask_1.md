# Cool Electronics Projects

## 1. Counter using 7 Segment Display

Components: 8051 Development Board, Seven Segment Display,Wires, Usb to Uart Converter

Working: We use a 8051 MicroController to count digits from 0 to 9999, we also use a usb to uart converter which converts Computer bytes to uart signals.

https://www.hackster.io/embedotronics-technologies/counting-from-0-to-9999-with-8051-using-7-segment-display-3cf151#toc-software-used-0

## 2. Arduino Wireless Weather Station

Components: Arduino Due, Arduino Nano, DHT22 Temperature Sensor,DS3231 Real Time Clock Module,nRF 24L01 Sparkfun Transciever Breakout,Breadboard, Wires, 	
3.2" TFT HX8357C

Working: First, we build a Transmitter/Sensor Circuit using Arduino Nano, Temperature Sensor to sense the temperature , NRF24L01 wireless module for wireless communication

Next, we build the reciever using An Arduino Due, DS3231 Real Time Clock module to maintain accurate timekeeping even when device power is off, DHT22 Temperature and Humidity Sensor, NRF24L01+ Wireless module to communicate with the other arduino, 3.2" Color TFT display, breadboard, wires
And our circuit is complete. Our circuit will sense and display the data on the TFT Display.

https://www.hackster.io/nickthegreek82/arduino-wireless-weather-station-dad470

![proj2](https://user-images.githubusercontent.com/107299579/173628399-8a38cd14-53a9-4820-a02c-d39340bcb00b.jpg)

## 3. ESP32 Door Alarm

Components: ESP32, Accelerometer,Wires, Breadboard, RGB LED, Membrane Keypad

Working: When we open the door, the accelerometer detects the movement (when the acceleration is above a certain threshold) and the ESP32 sends a mail to us notifying the same.

If we want to disarm the alarm, we must enter the hardcoded password through the membrane keypad. To enable it back again, we pres the * button after entering hte password which will arm the alarm again after 10 seconds.

https://www.hackster.io/SeanMabli2/esp32-door-alarm-b7636e

![proj3](https://user-images.githubusercontent.com/107299579/173629654-f86c2ec6-530e-41ba-82f1-b52b840a3317.png)

## 4. Raspberry Pi Automated Plant Watering with Website

Compomemts:  Raspberry Pi 3,Soil Moisture Sensor, Flexible Water Line, 5V Relay, 3-6V Mini Micro Submersible Pump, TOLI 120pcs Multicolored Dupont Wire, 5v Power Supply 

Working:  First we setup a web server using a python script in rpi, when the soil moisture goes below, a certain level, we program the water supply to flow water. Additionly, we can turn on the water supply manually through our website

https://www.hackster.io/ben-eagan/raspberry-pi-automated-plant-watering-with-website-8af2dc


![proj4](https://user-images.githubusercontent.com/107299579/173634333-31d91c0e-25a6-4c32-a4a4-2ed5e0546387.png)

## 5. Hand Gesture Volume Control

Components: 	
Adafruit QT Py, SENSE: Multipurpose Sensor Development Board, Adafruit Monochrome 128x32 SPI OLED graphic display, SparkFun Qwiic Cable Kit	

Working:Create an I2C bus between and OLED Display, Also, connect a Qwiic Cable between QTPYSAMD21 and SENSE. Now, whenever we move our hands in Anticlockwise direction, the sensor will sense it and increase the volume. Similarly for Clockwise movement, it decreases the volume.

https://www.hackster.io/ZBoss1234/hand-gesture-volume-control-01b9f0#team

## 6. Arduino Game Controller

Components: Arduio Leonardo based on ATmega32u4), Sparkfun Pro 5V/16Mhz, Resistor, PCB, Pushbutton

Working: Here we use pushbuttons as an alternative to keyboard keys to control the characters in the game

https://www.hackster.io/361085/arduino-game-controller-f3ffec


## 7. Water level Indiicator with SMS alert

Components: at89c51 ic, GSM Modem, Transformer, LED, Resistors, transistors, 

Working: Whenever the water level, reaches a pre- defined threshold the users are alerted through an SMS. This can be used an alert system in flood endagered zones with remote network access.

https://www.hackster.io/sumitgrover97/water-level-indicator-with-sms-alert-for-emergency-flood-a8b23f



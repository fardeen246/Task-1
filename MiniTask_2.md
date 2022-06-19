# ESP32 Door Alarm

## Problem Statement
- Designing a door alarm system which can sends an email notification along with a short video clip whenever someone breaches in.

## Ideation and Planning
- We use an Accelerometer to detect the door's acceleration while its being opened and we send an email to the owner whenever the door is opened witout disalarming it.
- Also, whenever someone opens the door without disalarming, we use the esp32 webcam to send a video clip which captures everything 10 seconds prior to the door opening through email.

## Pipeline
Accelerometer --> ESP32 --> Email Notification with video clip

| Part of the Pipeline to break | Feasibility | Advantages | Disadvantages |
| ----------------------------- | ----------- | ---------- | ------------- |
| Accelerometer | Feasible, very easy to get an Accelerometer from shops | Extremely low power consumption | An accelerometer can only measure change in velocity, therefore if the door is moved at constant velocity, it wont recognize it |
| ESP32 | Easily available in Market | It has an extensive set of libraries and can be used for a wide variety of applications | Beginners might find the coding very hard to follow | 
| Email Notification and video clip | Feasible using ESP32's Webcam and smtp module | The video clips can be used to identify the trespassers | The thiefs can block the webcam and then disable the alarm system |

## Prototyping Phase
- In the initial prototype, we can can use a simple setup using a breadboard, ESP 32 and accelerometer.
- For further development, we can use a physical lock system or add more security features like face/fingerprint detection.

# GPS Ambulance Tracker

## Problem Statement 
- To design an Ambulance GPS Tracker which sends real time location data to user via SMS. 

## Ideation and Planning
- First, we enable the Ambulance with a GPS tracking device.
- Then we use a GPS Modem to track the vehicle's coordinates and send this data through SMS using the microcontroller and GSM Modem.
- Further, we use pushbuttons to send precoded emergency messages.

## Pipeline
GPS Modem --> 8051 MicroController --> GSM Modem --> Emergency Pushbuttons

| Part of the Pipeline to break | Feasibility | Advantages | Disadvantages |
| ----------------------------- | ----------- | ---------- | ------------- |
| GPS Modem | Comparitively costly so financial constraints might become an issue | | |
| 8051 Microcontroller | Easily available in market | Has a dynamic and vast array of functionalitites | Coding is Hard |
| GSM Module | SMTP Module code is a bit hard to learn  | SMS is a very cheap service | SMS is slower compared to voice chats |
| Emergency Pushbuttons | Beginner friendly and easy to impement | Very easy to use | Can't send our own text as it is precoded |

- We can improve this model with more versatile code which takes user input messages and sends them to the driver 

## Prototyping Phase
- In the First Prototype, we can use a simple setup with a breadboard and GPS Module.
- Later we can improve the communiation service by sending user input messages.

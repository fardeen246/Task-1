# GPS Ambulance Tracker
## Troubleshooting 
-The sequence of working of the Project is: <br>
 GPS Modem --> 8051 MicroController --> GSM Modem --> Emergency Pushbuttons <br>
-If there are erors in the project, then it will be in one of the following components.
-Also, we follow the same order while checking for bugs, as the working of one component depends on the working of the previous componnent.
-First, we turn on the power supply and check whether the components are getting powered up using a tester.
- Also, the components might have internal shortages
-Then check for loose connections in the wires.
-Check the Microcontroller code for any errors.

## GPS Modem
- The GPS Tracker System might not be working properly, which can give us wrong location coordinates.
- Atmospheric Interfernce is also another issue, this can be intentional(Jamming, Spooofing) or non-intentional.
- Ephemeris (orbital path) data errors ==> The path of data transmission might also be another source. 
- Multi path errors => Different output values when data is transmitted through different paths.

## MicroController
- The SMS might not be transmitted because of errors in the Microcontroller Codes.
- The Microcontroller itself miight be faulty, to check this we can test a simple led blinking code with the Microcontroller <br>
  Here, if we don't get correct output ,Microcontroller is faulty or it might also be dur to the LED, in which case, test the code with other LEDs.
  
## GSM Modem
- The GSM Modem is another source for improper SMS working.
- The SIM Card of the Reciever's device might not be working properly.
- Two types of GSM error codes, CMS Error Codes ==> Network Related Issues (or) CME Error Codes ==> Device Related Issues

## Emergency Pushbuttons
- If the emergency messages aren't send properly, the error will most probably be here.
- The buttons might be broken or the Microcontroller code for sending thme might have bugs.

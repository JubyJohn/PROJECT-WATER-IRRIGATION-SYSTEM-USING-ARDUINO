# PROJECT-WATER-IRRIGATION-SYSTEM-USING-ARDUINO


## AIM
To create a water irrigation system using Soil-Moisture sensor interfaced with Arduino.


## COMPONENTS
1) Arduino UNO R3
2) Soil - Moisture Sensor Module
3) USB Cable
4) Jumper Wire


## CONNECTION
Soil-Moisture Sensor Module Pin Diagram

 ![Soil-Moisture-Sensor](https://github.com/user-attachments/assets/650e9cf0-f467-40e6-873e-1d7ae3852a2a)

<br> A0    = Output     ---->  A0
<br> VCC   = power supply  ---->  5V
<br> GND   = ground   ---->  GND


## PROCEDURE
<br> Step 1 : Interface Arduino board to Arduino IDE using port.
<br> Step 2 : Interface Arduino board with Soil-Moisture Sensor and print analog values on serial monitor.
<br> Step 3 : Modify the program to get desired outputs.


## OUTPUT

![Soil-Moisture-Sensor-Connections](https://github.com/user-attachments/assets/528272e4-d695-4151-a454-dfe889ce136c)
 
<br> On serial monitor , when done uploading
<br> WET LAND - MOTOR OFF  // when water is sensed by Soil-Moisture Sensor, LED turned OFF indicating motor off
<br> DRY LAND - MOTOR ON  // when no water is sensed by Soil-Moisture Sensor, LED turned ON indicating motor on


This library uses SoftwareSerial or HardwareSerial to communicate with servo controller

Wiring: 
The Tx pin of the servo controller is connected to the Rx pin of the Arduino, the Rx pin of the servo controller is
connected to Tx pin of Arduino, and the GND of the servo controller is connected to the GND of Arduino.
If you use SoftwareSerial, please connect to the corresponding tx and rx pin

Instructions:
Open the Arduino IDE. Menu->Include Library-> Add .ZIP Library ...-> Open the LobotServoControll.zip file
after this step is complete, please find the example of use in the menu-> Exampler-> LobotServoController  

This example is specific to Arduino UNO, if you use other models of Arduino, you need to make some changes, 
such as modifing Serail to Serial1

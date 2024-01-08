# Li-Fi Hazard Detection System
This repository contains the project work for the **Li-Fi** Project developed as part of the **CSE211 Course** at Ain Shams University, in the Fall Semester of 2023.

## Introduction
Li-Fi, or Light Fidelity, is a wireless communication technology that utilizes light to transmit data and information among different devices. This project aims to build a small prototype (Sender + Receiver) for hazard detection in homes using Li-Fi technology.


## System Layout
![System Layout](https://github.com/OmarMDiab/LIFI-Embedded-Project/raw/main/System_Layout.png)



| Sender Platform     | Receiver Platform | Alarms               |
|----------------------|-------------------|----------------------|
| TM4C123GH6PM         | Arduino           | Flashing Lamp        |
| Fume Sensor          |                   | Buzzer               |
| Ultrasonic Sensor    |                   | LCD Display          |
| Magnetic Sensor      |



## Operation:

Sensors detect danger (fire, Open Door, intrusion).
Data sent over light to the receiver platform or Bluetooth to a mobile phone.
Alarms (flashing lamp, buzzer, LCD display) activated with a corresponding message.

## Additional Features:

System control with two pushbuttons for start/stop operations.
Option to mute alarms with a dedicated pushbutton.
Alarms continue until mute pushbutton is pressed.
After pressing mute, alarms turn off after 5 seconds, but the system remains powered on.

## Authors
- [Youssef Mohamed](https://github.com/youssef-mohamed1809)
- [Seif Eldin](https://github.com/Seifeldin2510)
- [Omar Diab](https://github.com/OmarMDiab)

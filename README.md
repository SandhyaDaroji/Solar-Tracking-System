# Solar-Tracking-System
A Solar Tracking System is a device designed to automatically orient solar panels toward the sun to maximize energy absorption. Unlike fixed solar panels, which remain in one position, a solar tracker continuously adjusts the panel’s angle based on the sun’s movement throughout the day.

 Features
- Automatic sun tracking
- Increased efficiency compared to fixed panels
- Single-axis operation
- Low-cost implementation using Arduino
- Simple and scalable design

 Components Used
- Solar Panel
- Light Dependent Resistors (LDRs)
- Servo Motor
- Microcontroller (Arduino UNO)
- Power Supply 
- Connecting Wires, Resistors, Breadboard/PCB

Software & Libraries
- [Arduino IDE](https://www.arduino.cc/en/software)  
- Arduino C++  
- Libraries:  
  - `Servo.h` (for motor control)  

 Working Principle
1. LDR sensors detect the intensity of sunlight.  
2. The microcontroller compares LDR values.  
3. If a difference is detected, the motor rotates the panel toward the stronger light source.  
4. This continuous adjustment ensures the panel faces the sun throughout the day.  


---
layout: page
title: Summary Report
---
Here is the summary report of our project.

## Aim of project

The aim of our project is to create an intelligent automated flower pot, which waters the soil automatically when detects it dry. 
An important part was to develop our own sensor board with integarted Arduino. We wnated to create a capacitive sensor to detect the moisture of soil, instead of buying a ready made.


## Final product
The final products consist in a sensor board and an enclosure/base with reservoir and pump.
#### 3D modeling & printing
Jussi did the [3D model](https://github.com/txjt/SmartPot/tree/master/models/Concept2) design with Autodesk Fusion. 
It consists of several 3D-printed parts: a reservoir, a cover for reservoir used also as base for the flower pot (we bought at supermarket to ensure compatibility with existing pots in market), an arm were we put the peristaltic pump and a semi-circular water dispenser.  
Tiberio and Xiao printed the reservoir and its attached base of the flower pot. Jussi did the last printing of the arm and then we finally assembled the components together.
### Sensor & PCB
Tapio created the [schematics](https://github.com/txjt/SmartPot/blob/master/SmartPot_schematics.pdf) and designed the [PCB](https://github.com/txjt/SmartPot/blob/master/DigiFab_no_MCU.pdf). It is an all-in-one solution with capacitive sensor made out of two conductive lines very close and ramificated to act as a capacitor. On the same board there is the socket for an Arduino Nano and electronics to control both sensor and pump. Tapio and Tiberio created first an etched version of the bare sensor for testing purposes with oscilloscope(see [data](https://github.com/txjt/SmartPot/tree/master/%20osclilloscope) ). Then Tiberio and Xiao went to FabLab to mill a final version using Roland milling machine. It was a chance to learn how this process works. Even though we had some problems with the milling, because the plane was not aligned, Tapio fixed the PCB so Tiberio could start developing the [software](https://github.com/txjt/SmartPot/tree/master/software). 


## Lessons learned

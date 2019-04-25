---
layout: page
title: Summary Report
---
Here is the summary report of our project.

## Aim of project

The aim of our project is to create an intelligent automated flower pot, which waters the soil automatically when detects it dry.
An important part was to develop our own sensor board with integrated Arduino. We wanted to create a capacitive sensor to detect the moisture of soil, instead of buying a ready made.

## Final product
The final products consist in a sensor board and an enclosure/base with reservoir and pump.
#### 3D modeling & printing
Jussi did the [3D model](https://github.com/txjt/SmartPot/tree/master/models/Concept2) design with Autodesk Fusion.
{% include figure.html image="http://tiberiog.cacsite.com/tiberiog.cacsite.com/xiao/model1.png" caption="View of model" width="500" height="800" %}

It consists of several 3D-printed parts: a reservoir, a cover for reservoir used also as base for the flower pot (we bought at supermarket to ensure compatibility with existing pots in market), an arm were we put the peristaltic pump and a semi-circular water dispenser.  
Tiberio and Xiao printed the reservoir and its attached base of the flower pot. Jussi did the last printing of the arm and then we finally assembled the components together.
{% include figure.html image="http://tiberiog.cacsite.com/tiberiog.cacsite.com/xiao/finished.png" caption="3D-printed arm with water dispenser" width="500" height="800" %}

### Sensor & PCB
Tapio created the [schematics](https://github.com/txjt/SmartPot/blob/master/SmartPot_schematics.pdf) and designed the [PCB](https://github.com/txjt/SmartPot/blob/master/DigiFab_no_MCU.pdf).

{% include figure.html image="http://tiberiog.cacsite.com/tiberiog.cacsite.com/xiao/pcb-fin.png" caption="Final PCB draw" width="500" height="800" %}


It is an all-in-one solution with capacitive sensor made out of two conductive lines very close to act as a capacitor. On the same board there is the socket for an Arduino Nano and electronics to control both sensor and pump.

Tapio and Tiberio created first an etched version of the bare sensor for testing purposes with oscilloscope(see [data](https://github.com/txjt/SmartPot/tree/master/%20osclilloscope) ). Then Tiberio and Xiao went to FabLab to mill a final version using Roland milling machine. It was a chance to learn how this process works. Even though we had some problems with the milling, because the plane was not aligned, Tapio fixed the PCB so Tiberio could start developing the [software](https://github.com/txjt/SmartPot/tree/master/software).

{% include figure.html image="http://tiberiog.cacsite.com/tiberiog.cacsite.com/xiao/sw.png" caption="Arduino code" width="500" height="800" %}

For the final board we decided to use etching since it's a faster method and it guaranteed a perfect result:

{% include figure.html image="http://tiberiog.cacsite.com/tiberiog.cacsite.com/xiao/final-board.jpeg" caption="Final PCB" width="500" height="800" %}

{% include figure.html image="http://tiberiog.cacsite.com/tiberiog.cacsite.com/xiao/final-board2.jpeg" caption="Final PCB" width="500" height="800" %}

## Lessons learned

For us it was the first time designing an entire sensor by ourself. That was really challenging.
for Tapio, Xiao and Tiberio was also the first time with 3D modelling and 3D printing.

We also learned that the milling machine is not the best tool to create very large PCB since it takes lot of time and it's not easy to have a perfectly aligned mounting, this results in a non-uniform milling.

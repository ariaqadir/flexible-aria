---
layout: post
title: Smart Home Thermostat
date: 2023-11-30 19:32:20 -0500
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: SmartHome.jpg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [Teamwork, Electronics, Engineering]
---

[Project Video](https://youtu.be/AboBtPy3Abc?si=dfY4FVKgFEML-8DS)

### What?

Designing and building a smart home thermostat using an ESP32 microcontroller, capable of controlling a fan and heater based on thermistor sensor readings, with the ability to override settings via voice commands or wireless control through a web interface

### How?

#### Hardware

- The project consisted of several components connected to an ESP32 microcontroller.
- Voltage regulators were used to step down the voltage for 5V components and a buck convertor for higher current components such as the heater. 
- The board was powered externally with a 12V power supply through a barrel jack connector. 
- The microcontroller controlled a 2-channel relay to turn on/off the fan and heater based on temperature limits set by the user. 
- Both I2S and I2C communication protocols were used based. 

![](/assets/img/smarthomesch.png)

Soldered all the components on a prototying board with 22 gauge wires and male/female headers for components to be removable. 

![](/assets/img/SmartHomeSoldering.jpg)

#### Software

- Arduino code was used to write the software for the ESP32 microcontroller. 
- Hysteresis was implemented in the thermistor control logic to prevent rapid toggling of the fan and heater near the temperature threshold.
- An HTML website was created with buttons to control the fan and heater manually or automatically through wireless communication. 

![](/assets/img/smarthomesoftware.png)




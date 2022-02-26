# Plant Irrigation System using Capacitive Moisture Sensor
# Description

Irrigation is the most important practice and most intensive task in daily agriculture sector. To know when and how much to water the plants are two important aspects of irrigation. This can be done automatically using sensors and it can be determined when plants may need water. 

This plant irrigation system project is intended to observe the moisture content of the soil to provide a correct amount of irrigation to agricultural fields and make sure the effective growth within the plant. Irrigating the fields by switching the pump ON/OFF, this project automates the process manually. 

This project is implemented by using a microcontroller atmega328p, programmed like to collect input signals that measure the moisture content of soil through sensing arrangement. Because the capacitive moisture sensor is removed out from the water, the LCD indicates the dry condition. The microcontroller produces an output that drives a relay and operates the water pump on receiving the signal. Hence the system reduces human intervention and provides required irrigation to the field.

# Components Used

•	Atmega 328p Microcontroller

•	capacitive moisture sensor

•	Pump Motor

•	Relay

•	Relay Driver IC

•	Vtg Regulator IC

•	Resistors

•	Capacitors

•	Transistors

•	Cables and Connectors

•	Diodes

•	PCB and Breadboards

•	LED

•	Transformer/Adapter

•	Push Buttons

•	Switch

•	IC

•	IC Sockets

# Requirements

## High Level Requirements

| **ID** | **Descripion** |
| --- | --- |
| HLR1 |  It shell detect the moisture of the soil. | 
| HLR2 |  It shell communicate the input to the microcontroler. | 
| HLR3 |  It shell run the motor to provide water to needed  plants automatically. | 
| HLR4 |  It shell have a microcontroller. | 

## Low Level Requirements

| **HLR(ID)** | **LLR((ID)** | **Descripion** |
| --- | --- | --- |
| HLR1.1 | LLR1 |  It shell have a soil moisture sensor to detect the soil moisrture. | 
| HLR2.1 | LLR2 | It shell have a automatic controlling unit to perform all the tasks. | 
| HLR3.1 | LLR3 | It shell stop providing water to the plants after the soil moisture is increased. | 
| HLR4.1 | LLR4 | It shell have a ATmega328 microcontroller,relay and other components required. | 












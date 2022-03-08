# Table of contents
## 1)Introduction
###  i)Abstract
### ii)Simulation steps
## 2)Requirements
###  i)High Level Requirements
### ii)Low Level Requirements
## 3)SWOT ANALYSIS


# 1)Introduction

## i)Abstract

The main objective of this system is to handle the temperature inside the vehicle(car).When the user gets into the car the button sensor gets activated and then the user gets access to turn on the heater. The temperature inside the car is controlled by the temperature sensor by giving out  the analog value to micro controller Atmega328.    

## ii)Simulation

The operation of the heat control system is coded in embedded c and the working is demonstrated using a simulation software called \*\*\*Simul IDE\*\*\*.

This system is usually done in 3 tasks:

- When the two switches are closed, the first LED glows indicating the actuation of the system and the heater.
- Then the analog input from the temperature sensor is received and digitized using ADC.
- The digitized temperature input is visualized using Pulse Width Modulation.


# 2)Requirements


## i)High Level Requirements

|`               `ID|`          `Description|
| - | - |
|HLR\_01|Atmega microcontroller|
|HLR\_02|Changing the temperature|
|HLR\_03|Heater|


## ii)Low Level Requirements

|`                    `ID|`              `Description|
| - | - |
|LLR\_01	|Display the temperature|

# 3)SWOT ANALYSIS

- **Strengths**

` `Can change the temperature to the required value.

- **Weakness**

`       `Request should be implemented for each and every required temperature.

- **Opportunities**

Implementation in better code which serves various other purposes

- **Threats**

Security











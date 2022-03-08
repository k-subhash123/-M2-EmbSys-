# Seat Temperature control Automation

 ## Abstract

The main objective of this system is to handle the temperature inside the vehicle(car).When the user gets into the car the button sensor gets activated and then the user gets access to turn on the heater. The temperature inside the car is controlled by the temperature sensor by giving out  the analog value to micro controller Atmega328.    

## Simulation

The operation of the heat control system is coded in embedded c and the working is demonstrated using a simulation software called \*\*\*Simul IDE\*\*\*.

This system is usually done in 3 tasks:

- When the two switches are closed, the first LED glows indicating the actuation of the system and the heater.
- Then the analog input from the temperature sensor is received and digitized using ADC.
- The digitized temperature input is visualized using Pulse Width Modulation.


| [![cpp_check](https://github.com/k-subhash123/M2-EmbSys/actions/workflows/cppcheck.yml/badge.svg)](https://github.com/k-subhash123/M2-EmbSys/actions/workflows/cppcheck.yml) | [![Valgrind](https://github.com/k-subhash123/M2-EmbSys/actions/workflows/Valgrind.yml/badge.svg)](https://github.com/k-subhash123/M2-EmbSys/actions/workflows/Valgrind.yml) |
| --- | --- |
# step 1

| **OFF** | **ON** |
| --- | --- |
| <img width="900" alt="sml1" src="https://user-images.githubusercontent.com/98833482/157181792-cbe5bcad-2e81-495c-a2a3-757dc04dc7b2.png"> | <img width="904" alt="sml2" src="https://user-images.githubusercontent.com/98833482/157181844-5dda8c8c-f2ff-43c7-8491-8673121d5651.png"> |


# step 2

| **OFF** | **ON** |
| --- | --- |
| <img width="911" alt="sml3" src="https://user-images.githubusercontent.com/98833482/157182014-3d997037-56a8-419e-bab8-20d66e4b98df.png"> | <img width="909" alt="sml4" src="https://user-images.githubusercontent.com/98833482/157182054-ac228a0c-0025-40cc-8ed7-1ac319d03464.png"> |


# step 3

<img width="881" alt="sml5" src="https://user-images.githubusercontent.com/98833482/157182228-c459783f-4dc7-4196-a166-82f46243f990.png">

# Requirements
## Introduction
* The Vehicle Seat Heat Monitoring System is capable of maintaining of heat in the vehicles seats. In our project, the sensor will sense is the driver has been seated or not and if the driver seated then he need to set the temperature accordingly. Based on that our controller will set the heater to required temperature. The Heater will generate the heat and a LCD display will show requested the temperature. In our project we have used ATmega328 microcontroller along with temperature sensor, Switches, Heat generator,and LCD display,etc.

## Features
* The System will sense is driver or passenger seated or not.
* Driver or Passenger has the access to modify the temperature in the vehicle.
* As per Drivers request, Heater will generate the heat accordingly.
* It is best for European Countries.
* Low cost and robust system.
* Modular Approach.
## Components Used
* Power Supply
* Switches
* Temperature sensor
* LED
* LCD Display
* AVR Atmega 328 Microcontroller
## Software Used
* SimulIDE
* Visual Studio Code
# SWOT
## Strengths
* User Friendly
* Easy to alter the temperature inside the vehicles.
* Modular Approach
* Low cost and Robust system.
## Weakness
* Its only applicable for those countries which are having low temperature.
## Opportunities
* It can be implemented by having both Heater and AC.
## Threats
* Not suitable for average or high temperature places.
# 4W's and 1'H
## WHY
* Low cost and robust system.
## WHAT
* Vehicle seat heating system
## WHERE
* Used in Automotives
## WHEN
* At low Temperatures
## HOW
* The sensor will sense is the driver has been seated or not and if the driver seated then he need to set the temperature accordingly. Based on that our controller will set the heater to required temperature.
## Detail requirements
### High Level Requirements
| ID | Description |	Status |                                                                                                                                                                        | -----| -------- | ------ |
| HLR1 |	Microcontroller |      Implemented |
| HLR2 |	Temperature Sensor |	Implemented |
| HLR3 |	Heat Generation |	Implemented |
| HLR4 |	Display |	Implemented |
| HLR5 |	Software used |	Implemented |
### Low Level Requirements
| ID |     Description |	Status |                                                                                                                                                                   | ------ | ---------- | -------|
| HLR1_LLR1 |	ATmega328 |	Implemented |
| HLR2_LLR1 |	LM35 and ADC |	Implemented |
| HLR2_LLR2 |	ADC with PWM |	Implemented |
| HLR4_LLR1 |	LCD and LED |	Implemented |
| HLR5_LLR1 |	Visual Studio Code with AVR GCC compiler |	Implemented |
| HLR5_LLR2 |	SimulIDE |	Implemented |
# Design
## Structural Diagram

![structural diagram](https://user-images.githubusercontent.com/101049340/164472474-4429d520-db05-4d9a-8b38-b9abcac50c72.jpeg)

## Behavioural Diagram

![behavioural diagrams](https://user-images.githubusercontent.com/101049340/164472341-82ae7aa1-2f3b-41c5-91c4-7408955e2608.jpeg)

## Block Diagram

![bloock diagram](https://user-images.githubusercontent.com/101049340/164472207-ffc2ed25-4ad0-4521-ac9d-5c408bee71eb.jpeg)

# Simulations
## When Requirements not met
* Case1: When both the Seat Switch and HeaterSwitch turned off

![case1](https://user-images.githubusercontent.com/101049340/164469488-008ef586-c936-422d-8481-4ab3121f2e25.jpeg)

* Case2: When Seat Switch is on and Heater Switch is OFF

![case2](https://user-images.githubusercontent.com/101049340/164469607-c681fc1a-ae6e-450b-8578-463d52bfd871.jpeg)

* Case 3: When Seat switch is OFF and Heater Switch is ON

![case3](https://user-images.githubusercontent.com/101049340/164469698-19f25d4a-77fe-4231-b49c-1862eea1ecd1.jpeg)

* Case4: When both the switches are ON

![case4](https://user-images.githubusercontent.com/101049340/164469787-ae256b94-375c-4ba8-8d60-eaa44cfcb767.jpeg)

## Both Switches ON
| Duty Cycle |	Output | 
| ---- | ------- |
| 20% |	![20%](https://user-images.githubusercontent.com/101049340/164469899-31510efe-1f40-4489-892a-9c42be14c623.jpeg) |
| 40% |	![40%](https://user-images.githubusercontent.com/101049340/164470001-0524b15e-19f3-4d38-9d15-18d75a6d57bf.jpeg) |
| 70% |	![70%](https://user-images.githubusercontent.com/101049340/164470097-fafedf1c-a823-4a96-8734-64a1ea7c8a6e.jpeg) |
| 95% |	![95%](https://user-images.githubusercontent.com/101049340/164470178-55621b51-a00b-4644-b4d1-81e49d7a5c57.jpeg) |

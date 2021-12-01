## 8x8- LED Martrix
================

## Introduction
------------
A simple 8x8 LED Matrix interfacing to display the English characters using the AVR toolchain without the Arduino IDE.The 8x8 Matrix is a great way to add a square of light to just about anything, or even make a screen of a custom shape.This allows for incredibly tight pixel densities, and thus, a screen with less pixelation. 

## Software
-----------
 * SimulIDE
 * Visual studio code
 
 ## Components Used
 -------------------
1. 8x8 Matrix LED
2. AVR Atmega 328 Microcontroller
 
## Installation
------------
You will need to have the AVR toolchain installed on your system. This includes:
* avr-gcc
* avr-libc
* avrdude

## Cost and Feature
--------------------
The cost of the hardware and software design is fixed and one-time investment only.

## SWOT Analysis
### Strength
1.  The ultimate strength of this product is innovative and user-friendly.
2.  This product is long-lasting, and they can be used for display purpose.

### Weaknesses
1.  Always power supply is needed for this system to perform an operation.

### Opportunities
1.  We can use a solar panel in this system to reduce the power supply usage.
2.  We can add some additional advanced to it.
### Threats
1.  Nowadays people used to advertise and display things more attractive , LED displays will be more useful.

## 4W's and 1H
### Why
1.  To display the details or information attarctively.


### Where
1.  This system can be anywhere.


### Who
1.  It Can be used by anyone.


### When
1.This system can be used to display speed limits and traffic rules.


### How
1.  Giving different inputs we can find their desired output.

## Detail requirements
### High Level Requirements
| ID | Description | Status |
|----|-------------|--------|
| HLR_1 | Control Unit | Implemented |
| HLR_2 | Input Unit | Implemented |
| HLR_3 | Output Unit | Implemented |
| HLR_4 | Software Design | Implemented |

### Low Level Requirements
| ID | Description | HLR ID | Status |
|----|-------------|--------|--------|
| LLR_1 | AVR Atmega 328 Microcontroller | HLR_1 | Implemented |    
| LLR_2 | 8x8 Matrix LED | HLR_2 | Implemented |
| LLR_3 | Visual Studio Code & Simulide | HLR_3 | Implemented |




## Badges
|Build|Cppcheck|Codacy|
|:--:|:--:|:--:|
[![Build Status](https://github.com/karthikeyans99/M2_Embedded_8X8-LED-MATRIX/actions/workflows/compile.yml/badge.svg)](https://github.com/karthikeyans99/M2_Embedded_8X8-LED-MATRIX/actions/workflows/compile.yml) | [![Cppcheck](https://github.com/karthikeyans99/M2_Embedded_8X8-LED-MATRIX/actions/workflows/cppcheck.yml/badge.svg)](https://github.com/karthikeyans99/M2_Embedded_8X8-LED-MATRIX/actions/workflows/cppcheck.yml) | ![Codacy Badge](https://api.codiga.io/project/30189/status/svg)

## Folder Structure
Folder             | Description
-------------------| -----------------------------------------
`1_Requirements`   | Documents detailing requirements and research
`2_Design`         | Documents specifying design details
`3_Implementation` | All code and documentation
`4_Test_plan`      | Documents with test plans and procedures
`5_Report`         | Documentation of whole project
`6_Video`          | Working video of this project


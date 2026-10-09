# Android Password-Based Door Opener

## Project Overview

The Android Password-Based Door Opener is an embedded access-control system designed to operate a door through an Android mobile application using Bluetooth communication and password-based authorization.

The project integrates mobile application functionality, embedded C programming, microcontroller-based control logic, and electronic hardware to demonstrate a practical approach to automated door access.

## Objectives

- Develop a password-based electronic door-access system.
- Enable remote door operation through an Android application and Bluetooth communication.
- Use an 8051-family microcontroller to process access-control commands.
- Control a DC motor through an L293D motor driver.
- Integrate software and electronic hardware into a functioning prototype.

## Technologies and Components

| Component | Technology |
|---|---|
| Mobile interface | Android application |
| Communication | Bluetooth |
| Microcontroller | 8051 family (AT89S52/AT89C51) |
| Programming | Embedded C |
| Motor control | L293D motor driver |
| Actuator | DC motor |
| Other hardware | LCD, power-supply circuitry |

## System Architecture

**Android Application → Bluetooth Module → 8051 Microcontroller → L293D Motor Driver → DC Motor → Door Mechanism**

The Android interface provides password-based access and remote control. The microcontroller processes the received input and executes the control logic. When access is authorized, the motor driver operates the DC motor to control the door mechanism.

## Project Implementation

The project involved designing the control circuit, programming the microcontroller, integrating the Bluetooth interface, and testing the door-operating mechanism.

The original academic report contains the circuit schematic, component descriptions, operational explanation, and embedded C code. It also discusses keypad/DTMF circuitry in some sections; these descriptions are retained as part of the original report.

## Academic Relevance

This project demonstrates practical experience in:

- Embedded software development
- Access-control logic
- Mobile application and hardware integration
- Wireless communication
- Microcontroller programming
- Electronic circuit design and system testing

## Project Documentation

The repository includes the original final-year project report and supporting documentation.

The academic report is the primary reference for the original implementation. Separate Android application source code and independently buildable firmware files are not included unless added later.


## Project Scope

This repository documents an academic prototype developed as part of undergraduate engineering studies. It is not presented as a production-ready security or commercial access-control system.

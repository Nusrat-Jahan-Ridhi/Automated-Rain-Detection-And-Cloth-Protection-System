# Automated Rain Detection and Cloth Protection System

An Arduino-based automated clothes-drying system developed as part of the Computer Interfacing Laboratory course at Bangladesh University of Professionals (BUP).

## Overview

This project automates the process of drying clothes outdoors by monitoring rainfall, sunlight intensity, and accumulated drying time. When rain is detected, sunlight becomes insufficient, or the required drying time is reached, the system automatically moves the clothes rack under shelter.

## Features

- **Rain Detection:** Detects rainfall using a rain sensor and triggers protective movement.
- **Sunlight Monitoring:** Uses an LDR sensor to monitor light intensity.
- **Drying-Time Tracking:** Tracks accumulated sunlight exposure using a DS3231 Real-Time Clock (RTC).
- **Automatic Rack Movement:** Uses a stepper motor to move the clothes rack between outdoor and sheltered positions.
- **Continuous Monitoring:** Repeatedly checks sensor readings and drying status to make automatic decisions.

## Hardware Components

- Arduino Uno
- Rain sensor module
- Light Dependent Resistor (LDR)
- DS3231 Real-Time Clock (RTC) module
- 28BYJ-48 stepper motor
- ULN2003 stepper motor driver
- Connecting wires and supporting components

## Technologies and Tools

- Arduino
- Embedded C/C++ (Arduino programming)
- Arduino IDE
- Sensor interfacing and motor control

## How It Works

1. The system reads the rain sensor and LDR readings.
2. The RTC tracks the accumulated time the clothes spend drying in sunlight.
3. The Arduino evaluates rainfall, light intensity, and drying completion.
4. If rain is detected, sunlight is insufficient, or the required drying time is reached, the stepper motor moves the clothes rack under shelter.
5. When conditions permit, the system can move the rack back outdoors for drying.

## Project Images

Add photos of the completed prototype, sensor arrangement, and motorized rack in the `images/` folder.

Example:

![Project prototype](images/prototype.jpg)

## Project Report

The complete academic project report is available in the `docs/` folder.

## Academic Information

- **Course:** Computer Interfacing Laboratory
- **Course Code:** CSE-4102
- **Institution:** Bangladesh University of Professionals (BUP)
- **Project Type:** Academic Team Project
- **Submission Date:** December 2025

## Team Members

- Nazifa Tasin
- Shanjida Afrin
- Ishfar Bintey Haque
- Nusrat Jahan

## Future Improvements

- Improve weather-condition detection and sensor calibration.
- Add additional environmental monitoring capabilities.
- Enhance the mechanical design for practical household use.

# BuildSafe

## Structural Environment Monitoring Prototype

BuildSafe is an ESP32-based hardware prototype designed to monitor environmental and motion-related conditions around building structures.

The project explores how low-cost embedded systems can be used to collect environmental data, detect changes in motion or orientation, record measurements over time, and provide local alerts when configured thresholds are exceeded.

## Problem

Building maintenance can be difficult when changes in environmental or physical conditions are not noticed early.

BuildSafe explores a low-cost monitoring approach that can continuously collect measurements and make unusual changes easier to notice.

## Project Goals

- Monitor temperature and humidity.
- Measure motion and orientation using an inertial sensor.
- Display live measurements.
- Record measurements with timestamps.
- Provide local visual and audible alerts.
- Develop a compact prototype suitable for further testing.

## Hardware

The planned prototype uses:

- ESP32
- DHT11/DHT22 temperature and humidity sensor
- MPU6050 accelerometer and gyroscope
- RTC module
- MicroSD card module
- OLED/LCD display
- LEDs
- Buzzer

## System Architecture

Sensors → ESP32 → Data Processing → Display / Alerts / Data Logging

The ESP32 collects measurements from the sensors, processes the readings, displays the current status, records data, and activates alerts when configured conditions are exceeded.

## Project Status

🚧 **In development**

This repository will document the design, hardware development, firmware, testing, iterations, and final prototype.

## Safety Note

BuildSafe is a prototype monitoring system. It is not a certified structural-health monitoring system and does not independently determine whether a building is structurally safe or unsafe.

## Development

The project is being developed through iterative hardware testing and firmware development.

More documentation, circuit diagrams, firmware, test data, photographs, and build notes will be added as development progresses.

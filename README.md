# Autonomous Line Following & Parking Robot

An autonomous robotic vehicle developed using an Arduino Uno (ATmega328P) and programmed entirely in AVR Assembly language.

## Features

- Real-time line following using TCRT5000 IR sensors
- Autonomous parking detection using external interrupts
- PWM-based motor speed control
- Marker-based operating mode switching
- Lost-line safety timeout mechanism
- Finite State Machine (FSM) based control logic

## Hardware Used

- Arduino Uno (ATmega328P)
- TB6612FNG Motor Driver
- TCRT5000 IR Sensors
- IR Parking Detection Sensor
- Dual DC Motors
- 2×18650 Battery Pack

## Project Media

- Project_Report.pdf
- top_view.jpg
- bottom_view.jpg
- circuit_schematic.png
- demonstration video

## Source Code

- main.S – AVR Assembly firmware
- main.hex – Generated firmware image
- main.elf – Compiled executable

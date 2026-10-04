# Firmware

Embedded code for the ESP32 controlling the prosthetic's DC motors.

## Scope
- **Motor control** — PWM + direction logic to drive the N20 DC motors
- **UDP packet listener** — receives movement commands wirelessly and triggers the appropriate motor action
- **Data reading** — reads back speed/direction data from the motor encoders for use downstream (3D vis)

## Hardware Notes
N20 motors have 6 pins in 3 pairs:
- **M1/M2** — rotation control (high/low voltage sets direction). Connect to motor driver output only — never directly to the ESP32.
- **C1/C2** — encoder pins, report position/direction/speed via signal pattern

## Status
In progress — see Linear for current task breakdown (DC Motor Code, Reading in DC Motor Data).

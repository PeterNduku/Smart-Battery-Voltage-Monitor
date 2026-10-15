# Smart Battery Voltage Monitor

## Overview
A standalone battery voltage monitoring circuit designed to indicate battery condition through visual and audible alerts.

The circuit uses an LM358 operational amplifier configured as a comparator to monitor battery voltage against a reference threshold.

## Features
- 🟢 Green LED indicates a healthy battery voltage.
- 🔴 Red LED indicates a low battery voltage.
- 🔊 Buzzer provides an audible low-voltage warning.
- Adjustable voltage threshold (if configured in the circuit).

## Components
- LM358 operational amplifier
- Resistors and voltage-divider components
- 10 kΩ potentiometer
- Red LED and green LED
- BC547 NPN transistor
- Buzzer
- Battery power source

## Working Principle
The circuit compares the monitored battery voltage with a reference voltage.

- When the battery voltage is above the configured threshold, the green LED turns on.
- When the battery voltage falls below the threshold, the red LED and buzzer activate.

## Future Improvements
- Add an OLED display for real-time battery voltage readings.
- Display battery status on the screen.
- Improve voltage measurement accuracy and calibration.

## Project Status
**Current version:** Working hardware prototype  
**Planned upgrade:** OLED voltage and status display

## Applications
- Battery condition monitoring
- Low-voltage warning systems
- Educational analog electronics projects

---
*Developed as a practical electronics and circuit-design project.*

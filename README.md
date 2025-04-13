# BESS_DC_DC_Bidirectional

# DC-to-DC Bidirectional Power Converter for Microgrid-Based BESS

This project models a DC-to-DC power converter integrated with a lithium-ion battery energy storage system (BESS) for microgrid applications, focusing on voltage and current control using PWM-based switching.

## Overview

The system uses a Bidirectional DC-DC converter with MOSFETs, controlled by PI controllers to manage the charging and discharging of the lithium-ion battery. The system simulates the battery’s State of Charge (SOC) and ensures voltage stability under varying load conditions.

## Key Features
- Charging Mode: Battery charges when the switch is on. SOC increases slowly, and the converter maintains stable voltage (25.98V) with regulated current.
- Discharging Mode: Battery discharges when the switch is off. SOC decreases slightly, and the converter maintains stable load voltage (48V).

## Simulation Results
- Charging: SOC increases, battery current stabilizes, and load voltage remains constant at 48V.
- Discharging: SOC decreases slightly, battery current remains regulated, and load voltage remains stable.

## Dependencies
- MATLAB (R2020b or later)
- Simulink
- Simscape

## License
MIT License

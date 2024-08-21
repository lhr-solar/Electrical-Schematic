# Electrical-Schematic (WIP)
Electrical System Architecture for the 2024-2026 LHR Solar Vehicle

## Learnings from previous architecture (Daybreak)
1. ### Focus on mechanically sound system design. 
    Place systems in logical locations for enclosures and harnessing. Eliminate non-CAN signals that route across the car.

2. ### Standardize hardware design
    Bring the system under a shared hardware standard. Ensure that connectors are common across systems and are approved by electromechanical. Use SOM architecture where possible.

3. ### Plan first
    Lots of design decisions ended up being botch jobs deep into the design cycle. This left us hesistant to make changes to existing hardware as much of design had already been done and verified. Planning as much of the system architecture as we can before we dive into hardware design will help reduce the number of changes necessary down the line.

## Current ToDo
- Add Data Acq and Power Gen
- Update layout of lights and lighting boards
- Update Controls Daughter with display, dashboard LEDs, and dashboard switches
- Add fans to BPS Daughter
- Add battery breakout boards and scrutineering boards 
- Add High Voltage

![Electrical-Schematic](ElectricalSchem2024.pdf)
# Electirrpicttomiomer Build Instructions

First make sure that you have all of the parts. 

- D1: 3mm flat top LED (orange)
- D2: 3mm flat top LED (green)
- R1, R3: 0805 SMD resistor (10k ohms)
- R6: 0805 SMD resistor (3.3k ohms)
- R7: 0805 SMD resistor (12k ohms)
- THT Bourns PTV09A-1 single potentiometer (10k ohm)
- SMD SOT-23-5 opamp
- 2 jumper wires with male to female connectors
- electirrpicttomiomer pcb board
- 2 sensors
- Operating Guide

Steps:

- Solder the opamp to the back
- Solder R1 and R3 (they are 10k ohm resistors and are marked 1002)
- Bridge the pads marked R4 with solder. R4 is in series with the potentiometer and is not needed because the potentiometer covers the range of
resistance required.
- Solder the 3.3k ohm resistor (marked 3301) to R6.
- Solder the 12k ohm resistor (marked 123) to R7.
- Solder D1 (orange) to the front using through-hole soldering. 
- Solder D2 (green) to the front using through-hole soldering. 
- Solder the potentiometer to the front.
- Solder the 2 pin female header to the front (bottom). This is what you'll connect the two sensors.
- Solder the 4 header pins.
- Break the remaining 2 pin male header into two pieces so that each has one pin.
- Solder a male header pin to each of the sensors. 

How to use: 

- Power the badge with a Saintcon conference badge, minibadge expansion board or other means.
- Do not apply more than 3.3v to the board otherwise you could damage it.
- Follow the operating guide (RTFM)

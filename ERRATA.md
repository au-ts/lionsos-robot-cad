# Errata

This file lists issues with the power PCB.

## Power PCB Rev 2.1

No known issues.

## Power PCB Rev 2.0

5V power supply
* Feedback circuit incorrect. Resistor R12 uses a 33k resistor instead of a 57k resistor.
* Inductor undersized, should be 3.2-4.7uH instead of 2.2uH

Optocouplers
* U3 has MISO line connected backwards. Impossible for Arduino to send data back.

Misc.
* The power status LEDs incorrectly share a single resistor between them, the line must be separated and extra resistors must be placed.
* Power status LED resistor is too small.


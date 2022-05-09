# Marlin 3D Printer Firmware
This is a fork from [Marlin Firmware](https://github.com/MarlinFirmware/Marlin).  
Additional documentation can be found at the [Marlin Home Page](https://marlinfw.org/).  
Marlin is published under the [GPL license](/LICENSE).

## Configuration for BigBox
This is a Marlin 2.0.9.3 configuration for a BigBox Pro with a Hemera Revo Extruder, a BLTouch and TMC2130 drivers on X, Y, Z and E.
The printable files for the Hemera conversion can be found here : https://www.printables.com/model/200816-bigbox-hemera-with-mgn12h-linear-rail

The wiring should follow this wiring diagram in order to work with this configuration. If your implementation is different please modify the pins_RUMBA.h file and/or configuration files.

<img src="wiring.png" width="90%"></img> 

## Responsability
Please review the firmware before installing it on your board. This is provided as a guideline but may not work with your printer.

Things to watch out for :
- Motor direction
- Axis limits

I am not responsible for any damages or harm cause by the use of this firmware.
# Arduino Core for MKR1000 Studio H Software Variant

This repository contains the source code and configuration files of the Arduino Core for the MKR1000 (used on [Studio H Wireless Preset Managerr](https://www.studiohsoftware.com)). 
The modification is to assert VID=1209 and PID=FBA0 in boards.txt so that the Wireless Preset Manager displays expected information when used as a USB MIDI device. 

## Installation 
 
Create a folder called "hardware/fba/samd" in your sketches folder. Place the contents of this repository into that folder. 
This will add a new boards entry called "Arduino SAMD (32=bits ARM Cortex-M0+) Boards (in sketchbook)->Fueled by Anger (MKR1000)."



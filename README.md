# Marlin for E3V2 + SKR Mini
This is a Marlin firmware for the following printer setup:
* Ender 3 V2
* Original E3V2 display
* Extensible UI
* SKR Mini V2.0 board
* Satsana print head with BLTouch
* Dual gear extruder (139 steps/mm)
* Sensorless homing DISABLED

Fork of https://github.com/Jyers/Marlin, combined with some stuff of https://github.com/jernejp21/Marlin

You'll need to change the pinout of the display connector according to https://github.com/jernejp21/Marlin#hw-changes. The easiest way to do so is probably to bodge an extension cable from individual dupont male-female wires (such as [these](https://www.aliexpress.com/item/1005001705264902.html))

GPL License.
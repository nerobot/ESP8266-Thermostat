# ESP8266-Thermostat

Thermostat temperature control system using ESP8266 serial wifi boards, Openhab, and TMP112 temperature sensing IC.

## Current Status

Currently unusable - DO NOT USE

The project comes in 3 folders:

* The Openhab configuration files
* C code for the ESP thermometer devices
* C code for the ESP temperature control board

## Requirements

The ESP code was designed and compiled using the Windows SDK Toolkit available at http://www.esp8266.com/viewtopic.php?f=9&t=820 If installed correctly, you should have everything required to build and flash ESP8266 firmware.

## Installation

### Thermometer Sensor

* Load the example into Eclipse
* Open file "/include/user_config.h" and change the #defines as necessary (I've left them to the default ones in the example)


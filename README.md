# ESP8266-Thermostat

Thermostat temperature control system using ESP8266 serial wifi boards, Openhab, and DS1631 temperature sensing IC.

## Current Status

* Temperature Sensor Code and circuit
* Openhab setup for two temperature sensing boards and Raspberry Pi CPU temperature
* Thermostat control not setup

The project comes in 5 folders:

* The Openhab configuration files (a complete Openhab folder that can be copied and run)
* C code for the ESP thermometer devices
* C code for the ESP temperature control board (might not be up yet)
* Code for Node-Red
* Schematic and PCB designs

## Requirements

The ESP code was designed and compiled using the Windows SDK Toolkit available at http://www.esp8266.com/viewtopic.php?f=9&t=820 If installed correctly, you should have everything required to build and flash ESP8266 firmware.

## Installation

### Thermometer Sensor

* Load the projects into Eclipse
* Open file "/include/user_config.h" and change the #defines as necessary (I've left them to the default ones in the example)
* Open file "/user/user_main.c" and change the #define TOPIC to whatever is needed for that board
* Flash firmware

## Acknowledgements

* All the guys and galls over at esp8266.com for their hard on making these boards usable!
* Mikhail Grigorev for his work on the Windows Development Kit http://www.esp8266.com/viewtopic.php?f=9&t=820
* Tuan PM for his work on the native MQTT client for the esp8266 https://github.com/tuanpmt/esp_mqtt
* Anyone else I've missed out


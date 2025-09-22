# Changelog

## 0.0.7 (OpenSprinkler 2.3.3(182))

- Change base firmware version to 2.3.3(182):
   - ARP Proxy Fix
   - Improved water meter calculation for overlapping irrigation
   - Tennis Court: New program start and stop commands
   - Download the new (modified) firmware 2.3.3(182)
   - Support for [FYTA sensors](https://opensprinklershop.de/en/2025/08/25/fyta-sensoren/?v=15fc885b9ab6)
   - Support for RS485 Modbus stations ([See also here](https://opensprinklershop.de/en/zonen-mit-rs485-modbus-steuern/?v=15fc885b9ab6))
   - Monitoring and Control: New option “Reset in (s)” for a time-controlled reset of the monitor status
   - Latch: Stop all irrigation circuits: If no program or zone is running and this function is called, all zones will receive the stop impulse again
   - Virtual sensors for ETO and Radiation (requires weather service that supports this)
   - Fix for some W5500 adapters, adapted to 40MHz
   - Calculation of sunrise and sunset using internal formulas (instead of weather service)
   - Latest master branch of OpenSprinkler-Firmware installed (11.07.2025)
   - ARP table with 40
   - W5500 with 80MHz, ENC28J60 with 20MHz for faster network transmission
 
## 0.0.6 (OpenSprinkler 2.3.3(175))

- Change base firmware version to 2.3.3(175):
   - Added monitor and control feature "time"

## 0.0.5 (OpenSprinkler 2.3.3(174))

- Change base firmware version to 2.3.3(174):
   - Units lumen and lux added
   - Filter when logging: Data identical to the previous one is no longer saved
   - BugFix: Empty MQTT filter resulted in no value.
   - BugFix: OSPi RS485 SMT100 read error
- Undocumented change: Firmware version 174 can control the internal rain/soil sensor sn1/sn2 (without real sensors, for example via MQTT). But not “Flow” or “Program Switch”

## 0.0.4 (OpenSprinkler 2.3.3(173))

- Add ingress option to addon

## 0.0.3 (OpenSprinkler 2.3.3(173))

- Replace codebase to https://opensprinklershop.de modded firmware. it support Analog sensor API
- i386 image are not longer avaliable
- add amd64 and armv7 support

## 0.0.2 (OpenSprinkler 2.2.1.0)

- Add ARMv7 Support

## 0.0.1 (OpenSprinkler 2.2.1.0)

- Initial release

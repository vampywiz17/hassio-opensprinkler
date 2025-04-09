# Changelog

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

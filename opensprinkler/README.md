# Home Assistant Add-on: OpenSprinkler

Automate and Access Sprinklers from Anywhere
Keeping your lawn and flowers beautiful doesn't have to be stressful. OpenSprinkler unchains you from your sprinkler or irrigation control box, enabling you to program, run, or stop zones at any time from anywhere.
Whether you are at your desktop, laptop, tablet or phone; whether you are at home, office, or traveling on the road, you can access OpenSprinkler through any modern browser; or use our free apps available for all mobile platforms.

![Supports amd64 Architecture][amd64-shield] ![Supports armv7 Architecture][armv7-shield]

## About

This Add-on allows you to Install OpenSprinkler to Home Assistant. It use https://opensprinklershop.de modded firmware. The main difference that is support Analog sensor API. that mean it possible to add for example MQTT based sensors. More info: https://opensprinklershop.de/en/2023/01/29/analog-sensor-konfiguration-aktivieren/

## Configuration

Only need to setup the access port. Default: 5557

You access web interface at: http://ha_hostname:5557 (default). Web interface default password are: **opendoor**

Persistent files are saved to /data folder (Home Assistant default). If you delete these files, your config are lost!

## Home Assistant Integration

You able to use it with Home Assistant following integration:

https://github.com/vinteo/hass-opensprinkler

[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg

# Pinkywafer Home Assistant Config

[![Build Status](https://travis-ci.com/pinkywafer/Home-Assistant_Config.svg?branch=master)](https://travis-ci.com/pinkywafer/Home-Assistant_Config)

[![Buy me a coffee](https://img.shields.io/static/v1.svg?label=Buy%20me%20a%20coffee&logo=buy%20me%20a%20coffee&logoColor=white&labelColor=ff69b4&message=donate&color=Black)](https://www.buymeacoffee.com/V3q9id4)

[![Support Pinkywafer on Patreon][patreon-shield]][patreon]

This is my live Home Assistant config. 
It runs on an [XCY X30 Intel i7 4500U from banggood](https://www.banggood.com/XCY-X30-Mini-PC-Intel-Core-I7-4500U-Barebone-1_8GHz-Intel-HD-Graphics-4200-Windows-10-Dual-Core-Fanless-Mini-Desktop-PC-HDMI-VGA-WiFi-Nettop-HTPC-p-1479424.html)
Proxmox is installed on bare metal,  then this (production) Home Assistant runs in a VM.
A separate VM provides my Dev. env

This repo is validated by Travis CI

I also have containers for file sharing (nas), plex server, and a tuya convert container.

***

## Some statistics about my installation:

Lines of yaml code in my configuration (excluding secrets): 5333

Number of entities: 599

Type | Qty
-- | --
Alarm Control Panel | 1
Alert | 0
Automation | 78
Binary Sensor | 87
Camera | 12
Device Tracker | 22
Group | 0
Input Boolean | 2
Input Datetime | 1
Input Text | 5
Light | 20
Media Player | 15
Person | 3
Scene | 1
Script | 16
Sensor | 296
Sun | 1
Switch | 26
Weather | 5
Zone | 4

***

## HACS installed components

### Integrations
- [Anniversaries](https://github.com/pinkywafer/Anniversaries)
- [Authenticated](https://github.com/custom-components/authenticated)
- [Blitzortung.Org Lightning Detector](https://github.com/mrk-its/homeassistant-blitzortung)
- [Breaking Changes](https://github.com/custom-components/breaking_changes)
- [Browser Mod](https://github.com/thomasloven/hass-browser_mod)
- [Calendarific](https://github.com/pinkywafer/Calendarific)
- [Garbage Collection](https://github.com/bruxy70/Garbage-Collection)
- [HACS](https://github.com/hacs/integration)
- [Readme](https://github.com/custom-components/readme)
- [Spotcast](https://github.com/fondberg/spotcast)
- [Youtube](https://github.com/custom-components/youtube)

### Lovelace
- [Aftership Card](https://github.com/iantrich/aftership-card)
- [Battery Entity Card](https://github.com/cbulock/lovelace-battery-entity)
- [Button Card](https://github.com/custom-cards/button-card)
- [Card Mod](https://github.com/thomasloven/lovelace-card-mod)
- [Card Tools](https://github.com/thomasloven/lovelace-card-tools)
- [Custom Header](https://github.com/maykar/custom-header)
- [Entity Attributes Card](https://github.com/custom-cards/entity-attributes-card)
- [Github Card](https://github.com/ljmerza/github-card)
- [Ha (Lovelace) Card Weather Conditions](https://github.com/r-renato/ha-card-weather-conditions)
- [Layout Card](https://github.com/thomasloven/lovelace-layout-card)
- [Lovelace Card Preloader](https://github.com/gadgetchnnel/lovelace-card-preloader)
- [Mini Graph Card](https://github.com/kalkih/mini-graph-card)
- [Mini Media Player](https://github.com/kalkih/mini-media-player)
- [Multiple Entity Row](https://github.com/benct/lovelace-multiple-entity-row)
- [Simple Weather Card](https://github.com/kalkih/simple-weather-card)

***


Generated by the [custom readme integration](https://github.com/custom-components/readme)

[patreon-shield]: https://c5.patreon.com/external/logo/become_a_patron_button.png
[patreon]: https://www.patreon.com/pinkywafer
# Enphase Envoy Mqtt Json for Jeedom
## Introduction
A plugin for the [Jeedom](https://www.jeedom.com/) automation platform that takes a real time Json stream from an Enphase Envoy gateway and publishes to a mqtt broker. The data updates at least once per second with negligible load on the Envoy. This version works with 7.x.x and 8.x.x firmware.

Other plugins are available for Jeedom but I needed an higher refresh rate and a local connection to the gateway and v7-8 firmware compatibility.

## Warnings & Limitations
- This project is not officialy supported by Enphase any change made by Enphase could broke the implementation.
- This plugins does not retrieve individual solar panel data.

## Thanks
This project relies **heavily** on @vk2him work on the Enphase gateway for HomeAssistant available here https://github.com/vk2him/Enphase-Envoy-mqtt-json.

## Donation
If this project helps you, you can give me a cup of coffee<br/>
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://paypal.me/richardperezfr)

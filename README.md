# TRÅDFRI Remote Node is Node-RED Module for Home Assistant

[![Platform](https://img.shields.io/badge/platform-Node--RED-red)](https://nodered.org)
[![node-red-contrib-hass-flow](https://img.shields.io/github/v/release/racksync/node-red-contrib-hass-tradfri-remote)](https://github.com/racksync/node-red-contrib-hass-tradfri-remote/releases) [![last commit](https://img.shields.io/github/last-commit/racksync/node-red-contrib-hass-tradfri-remote)](https://github.com/racksync/node-red-contrib-hass-tradfri-remote/commit/)

![racksync-screenshot](https://github.com/racksync/node-red-contrib-hass-tradfri-remote/blob/main/images/screenshot.png?raw=true)

This repository contains the IKEA TRÅDFRI Remote Node-RED Node, which serves as an integration for Home Assistant. This Node allows you to easier interact with IKEA wireless remote control and automate various lighting scenarios using Home Assistant via Node-RED.

# Prerequisites
Before using the IKEA TRÅDFRI Remote Node-RED Node, you must have the following:

- Home Assistant installed on your system
- Zigbee2mqtt integration installed and configured on Home Assistant

(If you have not installed Home Assistant or Zigbee2mqtt, please refer to their respective documentation for installation and configuration instructions.)

# Installation

You can install the nodes using "Manage palette" from node-red kebab menu or run the following command in the root directory of your Node-RED installation

```
npm install node-red-contrib-hass-tradfri-remote --save
```

# Usage

Put "TRADFRI Remote" node instead of switch node, Now you can use the output as each click below.

| Output | Click/Action |
|---------------|---------------|
| `OUTPUT 1`    | toggle |
| `OUTPUT 2`       | toggle hold |
| `OUTPUT 3`   | arrow left click |
| `OUTPUT 4`         | arrow right click |
| `OUTPUT 5`        | brightness up click |
| `OUTPUT 6`   | brightness down click |
| `OUTPUT 7`   | arrow right hold |
| `OUTPUT 8` | arrow left hold |
| `OUTPUT 9`        | brightness up hold |
| `OUTPUT 10`        | brightness down hold |
| `OUTPUT 11`    | arrow left release |
| `OUTPUT 12`    | arrow right release  |
| `OUTPUT 13`    | brightness down release  |
| `OUTPUT 14`    | brightness up release |

                      
### Node-RED Node by RACKSYNC
- [Toggle Flows](https://flows.nodered.org/node/@racksync/node-red-contrib-hass-flow)
- [Tradfri Remote](https://flows.nodered.org/node/@racksync/node-red-contrib-hass-tradfri-remote)


![racksync-node](https://github.com/racksync/node-red-contrib-hass-tradfri-remote/blob/main/images/nodes.png?raw=true)


### Additional Resources
If you are new to Node-RED or Home Assistant, the following resources may be helpful:

- [Node-RED documentation](https://nodered.org/docs)
- [Home Assistant documentation](https://www.home-assistant.io/docs)
- [Zigbee2mqtt documentation](https://www.zigbee2mqtt.io)
- [IKEA TRÅDFRI Remote product page](https://www.ikea.com/gb/en/cat/products-products/)


### Tips

- It is recommended to always do a full deploy when you changed some of the nodes of this library to prevent unexpected behavior.
- Always use debug node to test message payload before using in Production.

### Automation Training

- [Product & Services](http://racksync.com)
- [Training & Course](https://facebook.com/racksync)

## [RACKSYNC CO., LTD.](https://racksync.com)

We helps our customers to create life easier across the border of entire technology stack with household and business solutions. We modernize life with Information Technology, Optimize and collect data to make everything possible, secure & trusty
\
\
RACKSYNC COMPANY LIMITED \
Suratthani, Thailand \
Email : devops@racksync.com \
Tel : +66 85 880 8885 

[![Home Automation Thailand Discord](https://img.shields.io/discord/986181205504438345?style=for-the-badge)](https://discord.gg/Wc5CwnWkp4) [![Github](https://img.shields.io/github/followers/racksync?style=for-the-badge)](https://github.com/racksync) 
[![WebsiteStatus](https://img.shields.io/website?down_color=grey&down_message=Offline&style=for-the-badge&up_color=green&up_message=Online&url=https%3A%2F%2Fracksync.com)](https://racksync.com)

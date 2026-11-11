## DKNR Domotic

Local-first home automation built with Docker, Node-RED and MQTT. Each project is a Docker container running Node-RED: device connectors talk to their devices on the local network whenever possible and publish simple values on a shared MQTT tree, the dashboard gathers them all.

Documentation: [dknr-domotic.github.io](https://dknr-domotic.github.io)

### Dashboard

| Project | Description |
| --- | --- |
| [dknr-domotic](https://github.com/dknr-domotic/dknr-domotic) | Dashboard and brain: gathers every DKNR entity by room, with history, scenes and modes |

### Device connectors

| Project | Description |
| --- | --- |
| [dknr-zigbee](https://github.com/dknr-domotic/dknr-zigbee) | Zigbee devices, through Zigbee2MQTT |
| [dknr-zwave](https://github.com/dknr-domotic/dknr-zwave) | Z-Wave devices, through Z-Wave JS UI |
| [dknr-rfxcom](https://github.com/dknr-domotic/dknr-rfxcom) | 433 MHz devices received by an RFXCom RFXtrx433 |
| [dknr-teleinfo](https://github.com/dknr-domotic/dknr-teleinfo) | Electricity meter teleinfo (TIC) |
| [dknr-apsystems](https://github.com/dknr-domotic/dknr-apsystems) | APSystems solar inverters, from the local ECU API |
| [dknr-zendure](https://github.com/dknr-domotic/dknr-zendure) | Zendure inverters and batteries, from the Zendure developer MQTT API |
| [dknr-daikin](https://github.com/dknr-domotic/dknr-daikin) | Daikin heat pumps, from the local API |
| [dknr-nuki](https://github.com/dknr-domotic/dknr-nuki) | Nuki smart locks, from the local bridge API |
| [dknr-verisure](https://github.com/dknr-domotic/dknr-verisure) | Verisure France alarm, from the Verisure cloud (no local access exists) |

### Voice and assistants

| Project | Description |
| --- | --- |
| [dknr-voice](https://github.com/dknr-domotic/dknr-voice) | 100% local voice control, with ESPHome satellites, Vosk and Piper (draft, not working yet) |
| [dknr-alexa](https://github.com/dknr-domotic/dknr-alexa) | Shares DKNR entities to and from Amazon Alexa, through Virtual Smart Home |
| [dknr-matter](https://github.com/dknr-domotic/dknr-matter) | Matter bridge exposing DKNR entities to Matter controllers (prototype) |

### Tools

| Project | Description |
| --- | --- |
| [workflows](https://github.com/dknr-domotic/workflows) | GitHub Actions workflows shared by all DKNR projects |
| [dknr-domotic.github.io](https://github.com/dknr-domotic/dknr-domotic.github.io) | Sources of the documentation site |

Docker images are available on [Docker Hub](https://hub.docker.com/u/jcpd) and in this organization's packages.

# Connecting devices
If you set up your own network as explained [here](#setting-up-the-network) or if you are already in reach of The Things Network gateways, you can start connecting devices to the network.

This section explains the configuration required for devices to connect to The Things Network, as well as step-by-step tutorials to build a simple prototype from scratch.

## Configuration
You can connect any LoRaWAN 1.0 compatible device to The Things Network. Since LoRa is a radio protocol, all packets are received by all gateways in reach that have a channel available. In order to identify your device, set the `DevAddr` (device address) to any value you like.

The demonstration back-end only processes packets encrypted with the public encryption keys. Use for both `AppSKey` (application session key) and `NwkSKey` (network session key) the key `2B7E151628AED2A6ABF7158809CF4F3C`.

## Tutorials
Follow these step-by-step tutorials to build your first prototype and connect it to The Things Network.

* [Hello world](https://github.com/TheThingsNetwork/examples/tree/master/basic/autonomo/hello-world) (SODAQ Autonomo and LoRabee RN2483)
* [Proximity](https://github.com/TheThingsNetwork/examples/tree/master/basic/autonomo/proximity) (SODAQ Autonomo, LoRabee RN2483 and Grove Ultrasonic Ranger)

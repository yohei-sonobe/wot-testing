# ECHONET

## ECHONET Lite Smart Home Appliances

### Remote: 11 devices 

#### Connection
All devices connect to the event environment by SSH port forwarding through a host that has public IP address.

Local relay IP address: `192.168.100.51`.

![Connection between Dublin and Ishikawa](./tpac2026-echonet-devices.png)

Participants in Dublin can access the devices in Ishikawa through Yohei's PC.
SSH port forwarding connects Yohei's PC and Xin's PC through AWS.

#### Devices

- [Smart Plug (1)](./TDFiles/smartPlug.td.jsonld)
- [Human Detection Sensor (2)](./TDFiles/humanDetectionSensor.td.jsonld)
- [Temperature Sensor (3)](./TDFiles/temperatureSensor.td.jsonld)
- [Humidity Sensor (4)](./TDFiles/humiditySensor.td.jsonld)
- [Electric Lock (5)](./TDFiles/electricLock.td.jsonld)
- [Open Close Sensor (6)](./TDFiles/openCloseSensor.td.jsonld)
- [SmartPlug/Fan (7)](./TDFiles/smartPlug2.td.jsonld)
- [Air Conditioner (8)](./TDFiles/airconditioner.td.jsonld)
- [Ceiling Light (9)](./TDFiles/ceilingLight.td.jsonld)
- [Air Cleaner (10)](./TDFiles/airCleaner.td.jsonld)
- [Human Detection sensor(11)](./TDFiles/humanDetectionSensor2.td.jsonld)

You can confirm the operation of remote devices via web camera!

Have fun!

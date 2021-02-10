# tasmota-zigbee-admin
Node-Red Dashboard to administrate Tasmota Zigbee bridges and devices

right now the following features are implemented: 

*  table of all tasmota devices with link to their webinterfaces and info about their rssi, uptime etc..
*  table of all tasmota zigbee bridges with link to their webinterfaces and info about their rssi, uptime etc..
*  table of all zigbee devices with info about their bridge, rssi, battery, last seen, status...
*  enable zigbee pairing on a seletec zigbee bridge.
*  renaming of zigbee devices from a list of all devices
*  notification for devices beeing offline and empty batteries
*  autodiscovery of zigbee sensors for HomeAssistant
*  autodiscovery of zigbee lights for HomeAssistant

import the flow.json into your node-red instance and configure the mqtt nodes to your broker.

required node-red plugins: 
  * node-red-dashboard
  * node-red-node-ui-table
  
  if using node-red < 1.1, please install plugin node-red-node-group aswell.

![Alt text](Tasmota_Zigbee_Admin_latest.png?raw=true "Screenshot")

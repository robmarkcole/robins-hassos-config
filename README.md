# robins-hassos-config
My config for my HassOS instance. I had experimented with the 64 bit raspberry pi but have reverted to 32 bit after encountering multiple compatability issues with hassio addons.

Currently I have a cheap USB camera and a BBC microbit connected to my pi.

<p align="center">
<img src="https://github.com/robmarkcole/robins-hassos-config/blob/master/images/setup.JPG" width="900">
</p>

## BBC-microbit
Configured as per this repo https://github.com/robmarkcole/HASS-BBC-envirobit Will be used as sensor node and remote control.

<p align="center">
<img src="https://github.com/robmarkcole/robins-hassos-config/blob/master/images/usage.png" width="900">
</p>

## Add-ons

1. Configurator with ipanel https://www.home-assistant.io/addons/configurator
2. SSH & Web Terminal with ipanel https://github.com/hassio-addons/addon-ssh/blob/v3.2.0/README.md
3. Samba share https://www.home-assistant.io/addons/samba/
4. MQTT Server & Web client: https://github.com/hassio-addons/addon-mqtt/blob/master/README.md
5. MariaDB with recorder for database server: https://www.home-assistant.io/addons/mariadb/
6. Motion camera detection: https://github.com/HerrHofrat/hassio-addons
7. esphomelib for DIY devices: https://esphomelib.com/esphomeyaml/index.html#features

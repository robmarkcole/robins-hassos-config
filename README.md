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
Try to limit your addons, as too many will make your system unstable.
1. IDE -> replaces samba & configurator: https://github.com/hassio-addons/addon-ide
2. SSH & Web Terminal -> SSH backup:  https://github.com/hassio-addons/addon-ssh/blob/v3.2.0/README.md
3. MQTT Server & Web client: https://github.com/hassio-addons/addon-mqtt/blob/master/README.md
4. Motion camera detection: https://github.com/HerrHofrat/hassio-addons
5. Portainer: https://github.com/hassio-addons/addon-portainer

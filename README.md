# Actions

* Erst Pin Werte setzen, dann raus oder rein
* Magnetschalter integrieren
* Test Installation Garage 2
* WLAN Test
* Passwort change pi
* Passwort change Homeassistant
* Let's encrypt
* DuckDNS
* Port forwarding

# Raspberry Pi
## Headless WiFi configuration

# Homeassistant

## Starting​, stopping, restarting Homeassistant Service
```
sudo systemctl start home-assistant@homeassistant.service
sudo systemctl stop home-assistant@homeassistant.service
sudo systemctl restart home-assistant@homeassistant.service
```

## Check YAML configuration
Log in as the pi account and execute the following commands:
```
$ sudo su -s /bin/bash homeassistant
$ source /srv/homeassistant/bin/activate
$ hass --script check_config 
```
This will output any errors in your configuration files to console.

# MQTT


# ESP8266 / Nodemcu / Arduino
## Hardware
## Setup up environment
## WiFi connection
## MQTT
### Subscribe
### Publish



# Raspberry Pi image inc. WiFi Drivers
Raspbian Image with Mediatek and Realtec WiFi drivers compiled and installed.
These devices are not supported by default and its drivers are hard to install.
Most of the cheap USB wifi adpaters from ebay have these chips.

TP-LINK TL-WN725N

Realtek 8188eu

mt7601u

MediaTek 7601u


#Setting up
Edit your "/etc/network/interfaces" file so that it looks like the one given

Just copy the wlan0 part and replace 'wlan0' with 'ra0'

Or

You can navigate to network folder and download the file and replace it

cd /etc/network

sudo rm interfaces

sudo wget https://raw.githubusercontent.com/CyberLeito/RaspberryPi/master/interfaces


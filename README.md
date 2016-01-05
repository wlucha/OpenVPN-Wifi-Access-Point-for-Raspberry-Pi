# OpenVPN-Wifi-Access-Point-for-Raspberry-Pi
OpenVPN Wifi Access Point for Raspberry Pi

This is a bash script based on "Hotspot – WiFi Access Point" from JACEK TOKAR.
Link to the original script: http://raspberry-at-home.com/hotspot-wifi-access-point/

This script installs a Wifi Access Point on your Raspberry Pi which tunnels your traffic through OpenVPN.
Additionally it's possible to install VPNBOOK.com OpenVPN certificates.

Hardware 
- Raspberry Pi model B+ (or B)- Ethernet is required
- Ethernet cable
- WiFi adapter - Not all WiFi adapters work
- SD Card (4GB or greater) with Raspbian on it
- Power supply for your Pi & a Micro USB cable
- USB Console cable (optional) - this makes it a little easier to debug the system
- Case for your Pi (optional)
- A SD or MicroSD card reader (optional)

Preparations
- Install the OS (Raspbian) onto your SD card
- Boot the Pi and configure 
- Don't forget to change the default password for the 'pi' acccount!
- Set up and test the Ethernet and Wifi connection

Installation
- Download the script to your Raspberry Pi
- chmod +x openvpn_gateway.sh
- sudo ./openvpn_gateway.sh
# Deauth_Detection_nodemcu
It is a device which helps to find if any hacker attacking our wireless network or not. It can programmed with c.<br />

# REQUIREMENTS:
1.Node mcu module (esp8266)<br />
2.Power source (powerbank)<br />
3.Usb cable<br />
4.Nodemcu flasher<br />

# Installation:
# Windows users:
1.Download ad install nodemcu flasher in your windows machine.<br />
2.Download the deauth_detection.bin file to your pc.<br />
3.Now open node mcu flasher in your pc.<br />
4.Conect your node mcu module using usb cable.<br />
5.Selct the COM port in node mcu flasher and in binaries select deauth_detection.bin.<br />
6.Now click on flash and wait for 3 or 4 min.<br />
7.Now connect the node mcu module to power bank and place near the router you want to secure.<br />

# Node mcu flasher link:
32 bit:<br />
https://github.com/nodemcu/nodemcu-flasher/tree/master/Win32/Release <br />
64 bit:<br />
https://github.com/nodemcu/nodemcu-flasher/tree/master/Win64/Release <br />

# Usage of node mcu:
Refer this link: https://github.com/nodemcu/nodemcu-flasher#usage <br />

# Linux users:
1.open terminal and type fllowig command to install esptool.<br />
 <b> sudo pip install esptool</b><br />
2.Now download the deauth_detection.bin.<br />
3.To flash bin file to node mcu use following command.<br />
  <b>esptool.py --port COM4 write_flash 0x0000 deauth_detection.bin </b> (Here COM port is differs)<br />
4.Now connect the node mcu module to power bank and place near the router you want to secure.

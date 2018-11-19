# Deauth_Detection_nodemcu
It is a device which helps to find if any hacker attacking our wireless network or not.

# REQUIREMENTS:
1.Node mcu module (esp8266)
2.Power source (powerbank)
3.Usb cable
4.Nodemcu flasher

# Installation:
# Windows users:
1.Download ad install nodemcu flasher in your windows machine.
2.Download the deauth_detection.bin file to your pc.
3.Now open node mcu flasher in your pc.
4.Conect your node mcu module using usb cable.
5.Selct the COM port in node mcu flasher and in binaries select deauth_detection.bin.
6.Now click on flash and wait for 3 or 4 min.
7.Now connect the node mcu module to power bank and place near the router you want to secure.

# Node mcu flasher link:
32 bit:
https://github.com/nodemcu/nodemcu-flasher/tree/master/Win32/Release
64 bit:
https://github.com/nodemcu/nodemcu-flasher/tree/master/Win64/Release

# Usage of node mcu:
Refer this link: https://github.com/nodemcu/nodemcu-flasher#usage

# Linux users:
1.open terminal and type fllowig command to install esptool.
  sudo pip install esptool
2.Now download the deauth_detection.bin.
3.To flash bin file to node mcu use following command.
  esptool.py --port COM4 write_flash 0x0000 deauth_detection.bin  (Here COM port is differs)
4.Now connect the node mcu module to power bank and place near the router you want to secure.

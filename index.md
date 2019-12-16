_____________________________________________________________________________________
IPFire on a Raspberry Pi
_____________________________________________________________________________________
Url’s used:
IPFire

https://www.ipfire.org/
https://www.ipfire.org/download/ipfire-2.23-core138

Etcher
https://www.balena.io/etcher
_____________________________________________________________________________________
Components:
- Raspberry Pi 3
- 32 GB SD Card
- USB-to-LAN adapter
- USB Keyboard
- Monitor with HDMI
- Win / Mac / Linux computer to download and flash the SD Card
_____________________________________________________________________________________
Steps:
1) Download the arm image from https://www.ipfire.org/
2) Extract the image from the file you have downloaded.
3) Flash your SD Card with the IPFire image you extracted using Etcher.
(Or your preferred tool)
4) If you plan on using the HDMI output and USB Keyboard. You need to edit the uENV.txt file
on the flashed SD Card and change it as shown below:
SERIAL-CONSOLE=ON
To
SERIAL-CONSOLE=OFF
5) Remove the SD Card from your computer and insert it into the Raspberry Pi.
6) Connect all the components to the Raspberry Pi and power it on
7) Follow the usual IPFire installation / configuration steps.
8) Configure the IPFire you installed as you need.
--END--
PDF version here - https://www.hendgrow.com/ugs/HowTo-install-IPFire-on-a-Raspberry-Pi.pdf
https://HendGrow.com

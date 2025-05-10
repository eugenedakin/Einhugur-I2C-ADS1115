# Einhugur-I2C-ADS1115
Uses the Einhugur I2C library to read and analogue-to-digital chip

The ADS1115 is widely used with sensors to read signals from pressure sensor, light sensors, and temperature sensors. Other uses include industrial automation , Data Acquisition Systems, medical devices, environmental monitoring such as humidity, embedded electronic systems that require high resolution input, robotics, and audio applications for signal processing and sound capture.

![](https://github.com/eugenedakin/EinhugurI2CADS1115/blob/main/ADS1115ScreenGrab.png)

The Einhugur plugin can be installed in the Xojo IDE for use with the Raspberry Pi OS and the download link is at (https://www.einhugur.com/Downloads/Plugs/I2CPlugin.zip)

Install instructions are:
1) install Raspberry Pi OS (64-bit)
2) Open a terminal and type the following commands:
3) sudo apt install swig python3-dev
4) sudo apt install python3-setuptools
5) sudo apt install libunwind8
6) create an ADS example program and copy the program and libraries to the RaspberryPi Desktop, and add the Einhugur plugin to the Xojo IDE
7) give the executable permission to run with something like: 'sudo chmod +x ADS'
8) run the program with something like: 'sudo ./ADS'

![](https://github.com/eugenedakin/EinhugurI2CADS1115/blob/main/ADS1115Rev1Breadboard.png)


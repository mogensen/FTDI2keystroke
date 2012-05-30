FTDI2keystroke
==============

A script to generate keystrokes from FTDI devices, communication on serial /dev/cu.xxxxxxx

Usage
------------

1. Install the FTDI drivers from http://www.ftdichip.com/FTDrivers.htm
2. Insert the USB FTDI device
3. Run the `FTDI2keystroke` script naming the usbserial device that you want to use

( ex. `./FTDI2keystroke /dev/uc.usbserial-A800f8sK`)

Supported devices
-----------------

The script is written to allow using the "RFID Starter Kit" from [sparkfun](http://www.sparkfun.com/products/9875)

* USB RFID board with `ID-2`,`ID-12` or `ID-20` RFID reader
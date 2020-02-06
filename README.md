Adafruit_TLC5947 [![Build Status](https://travis-ci.com/adafruit/Adafruit_TLC5947.svg?branch=master)](https://travis-ci.com/adafruit/Adafruit_TLC5947)
================

<a href="https://www.adafruit.com/product/1429"><img src="assets/board.jpg?raw=true" width="500px"></a>

This is a library for our Adafruit 24-channel PWM/LED driver

Tested and works great with the Adafruit TLC5947
* http://www.adafruit.com/products/1429

These drivers uses SPI to communicate, 3 pins are required to  
interface: Data, Clock and Latch. The boards are chainable

Adafruit invests time and resources providing this open source code, please support Adafruit and open-source hardware by purchasing products from Adafruit!

Written by Limor Fried/Ladyada for Adafruit Industries.  
BSD license, check license.txt for more information
All text above must be included in any redistribution

To install, use the Arduino Library Manager and search for "Adafruit TLC5947" and install the library.

Version updated to support blanking control for the write phase of the driver. Blanking resets the internal oscillator of the TLC5947 and helps to reduce any flickering caused by updating the outputs during the PWM cycle of the TLC5947. Blanking resets the PWM cycle. This optional blanking mode requires a four wire connection to the Adafruit_TLC5947.

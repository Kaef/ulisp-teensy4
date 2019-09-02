# Note for Teensy-4.0 board support
This is a fork of ulisp.arm with added support for Teensy-4.0 board.
The board is made by pjrc, please see documentation at there webpage.

This is just a 'proof of concept'! I wanted to find out if I can made
a ulisp version for this board.
I started with ulisp for arm processors (currently M0+, M0, M3, M4 are supported)
and it needed just a few changes to get it up and running.
I did not test any hardware features of the board, I just wanted to run ulisp.
As long as there is no interest from the comunity, I will not go on doing additional tests.

## iMXRT1062 basic features (for details look at pjrc page)
* ARM cortex M7 processor at 600 MHz with a NXP iMXRT1062 chip
* 1024k RAM, 2048k flash
* USB, CAN, I2S, SPI, I2C, ADC, RTC, FP unit and much more
* needs 0.42 seconds for the (tak 18 12 6) benchmark,
  which is about 14 times faster than the Maxim MAX32620FTHR,
  currently the fastest ulisp board and about 17 times faster than the ESP32!

# ulisp-arm
A version of the Lisp programming language for boards based on the ARM processor:

* Arduino Due, Zero, and MKRZero.
* Adafruit ItsyBitsy M0, Feather M0, and Gemma M0.
* Adafruit Metro M4, ItsyBitsy M4, Feather M4, and Grand Central M4.
* BBC Micro Bit.
* Maxim MAX32620FTHR.

For more information see: http://www.ulisp.com/

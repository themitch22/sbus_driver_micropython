This fork is for SBUS for the micropython implementation for the Raspberry Pi Pico RP2040

The UART init does not invert the incoming signal. I used an inverter circuit going to the UART1 pin on the pico.

# sbus_driver_micropython
a Micropython driver for the SBUS protocol

It supports 16 standard Channels plus 2 digitals.

It has been tested only on the below FrSky receivers:
- X8R
- X6R
- X4R

An example of usage can be found in the file sbus_driver_example.py

To run the example you have to connect the sbus receiver signal pin to the pyboard pin Y10 (UART #3)


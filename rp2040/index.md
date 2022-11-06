---
title: RP2040
author: Scott CJX
---

# RP2040

My research touches on the software development for RP2040 on the [Raspberry Pi Pico Development Board](https://www.raspberrypi.com/products/raspberry-pi-pico/) and the hardware development of a minimal RP2040 powered board.

<hr>

## Software
The RP2040 can run on either [C/C++](https://github.com/raspberrypi/pico-sdk) or [MicroPython](https://docs.micropython.org/en/latest/index.html). 
The RP2040 also boasts 2 Programmable Input/ Output (PIO) which can be programmed using a modifed version of assembly language \([PIO ASM](https://www.raspberrypi.com/news/what-is-pio/)\) , accessable in both C/C++ and MicroPython.

### Flashing the RP2040 
The RP2040 can be programmed by either Serial Wire Debug (SWD) or USB Flashing Format (UF2).

It is recommended to use the latter for beginners.

[Useful article](https://www.tomsonelectronics.com/blogs/news/how-to-set-up-raspberry-pi-pico-rp2040-microcontroller)


### C/C++
Installing the RP2040 C/C++ SDK: <br>

Raspberry Pi provides a [Quickstart Guide](https://github.com/raspberrypi/pico-sdk#quick-start-your-own-project) on installing the pico-sdk.

Codes can be compiled locally or using Docker.

I have opted to use the [Docker](./software/pico_sdk_docker.md) method to compile my C/C++ codes for RP2040.


### MicroPython
Micropython comes installed in the Pi Pico by default


## Hardware


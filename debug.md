# Debuggers

Resources related to debugger hardware and firmware.

## Interfaces

### CMSIS-DAP

Open interface by ARM for communicating with a hardware debugger

* [mBed CMSIS-DAP](https://developer.mbed.org/handbook/CMSIS-DAP)
* [Keil CMSIS-DAP](http://www.keil.com/pack/doc/CMSIS/DAP/html/index.html)


## Hardware

### OpenSDA

OpenSDA is a hardware implementation of CMSIS-DAP with a variety of different firmwares that can be run on top.

* [NXP User's Guide](http://www.nxp.com/files/32bit/doc/user_guide/OPENSDAUG.pdf)
* [SEGGER firmware](https://www.segger.com/opensda.html)
* [PE Micro firmware](http://www.pemicro.com/opensda/)
* [DAPLink](https://github.com/mbedmicro/DAPLink) tested version v0241 on FRDM-K64F

## Host Software

### OpenOCD

* Communicates with a variety of devices, particularly: CMSIS-DAP, FT2232, STLink hardware.

* [OpenOCD](http://openocd.org/)

### pyOCD

Communicates exclusively with CMSIS-DAP hardware.

* [Github](https://github.com/mbedmicro/pyOCD)

### J-Link GDB Server

* [Segger](https://www.segger.com/jlink-gdb-server.html)

TODO: ARM semi hosting?

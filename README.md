# RISCOS miscellaneous stuff
This repository contains stuff related to my exploration of the RISC OS

Current the following things are here:

### ds1307_i2c

A small utility written in BBC Basic which shows how to access (write/read) to I2C devices and decoding the result into a human readable form. The example assumes that a DS1307 RTC is connected to address 0x68. The following datasheet was used to lookup the communication protocol of the device:

https://web.archive.org/web/20220114212710/https://datasheets.maximintegrated.com/en/ds/DS1307.pdf

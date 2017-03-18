# arom2bin

## What is arom2bin

arom2bin is a simple script to convert Amiga 512kB ROM files to two 512kB files suitable for programming onto two 27C400 EPROM chips.

## Requirements

srec_cat executable

## Synopsis

```
arom2bin "Kickstart v3.1 r40.68 (1993)(Commodore)(A3000).rom"
```

This will create the two files `Kickstart v3.1 r40.68 (1993)(Commodore)(A3000).LO.bin` and `Kickstart v3.1 r40.68 (1993)(Commodore)(A3000).HI.bin` that need to be programmed onto two EPROMS that will fit the Amiga 3000's U180 and U181 sockets respectively.


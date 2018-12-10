nRF51 and nRF51dk
=================

The nRF51 was supported in Tock up to Tock 1.3. However, the nRF51 is not a
good match for Tock, as it has little RAM and a very basic MPU. The relevant
code has been moved here, and should compile and run against Tock 1.3.


Usage
-----

Using this archived version should work very similar to mainline Tock. With
`rustup` installed:

```
$ cd boards/nrf51dk
$ make
$ make flash   # Load the kernel on the board.
```

# VertigoIMU Serial Numbers

_A compact 11dof inertial datalogger with AHRS_

[Home](index.md)

### Vertigo Classic

* 1101: [OBSOLETE] Completed rev 1.1 board with bluetooth
* 1102: [OBSOLETE] Semi-complete rev 1.1 board
    Never tested, was made obsolete by rev 1.2
* 1201: [DECOMMISSIONED] Rev 1.2 board, has lifted pads on IMU but still works.
    Has 2.2uH/1uF boost reg mod. With JS.
* 1202: [DECOMMISSIONED] Rev 1.2 board. Has 2.2uH/1uF boost reg mod.
    **Reg failed 4/7/17 - dismantled for parts.**
* 1203: [OPERATIONAL] Rev 1.2 board. Has 2.2uH/1uF boost reg mod. With Angelo.
* 1301: [OPERATIONAL] Rev 1.3 board, hand soldered 31-JUL-17.
* 1302: [OPERATIONAL] Rev 1.3 board, hand soldered 31-JUL-17.
* 1303: [OPERATIONAL] Rev 1.3 board, hand soldered 12-AUG-17.
* 1304: [OPERATIONAL] Rev 1.3 board, reflowed 07-SEP-17.
* 1305: [OPERATIONAL] Rev 1.3 board, reflowed 07-SEP-17.
* 1306: [OPERATIONAL] Rev 1.3 board, reflowed 07-SEP-17.
* 1307: [OPERATIONAL] Rev 1.3 board, reflowed 07-SEP-17.
* 1308: [OPERATIONAL] Rev 1.3 board, reflowed 07-SEP-17.
* 1309: [OPERATIONAL] Rev 1.3 board, reflowed 07-SEP-17.
* 1310: [OPERATIONAL] Rev 1.3 board, reflowed 07-SEP-17.
* 1311: [OPERATIONAL] Rev 1.3 board, reflowed 07-SEP-17.
* 1312: [OPERATIONAL] Rev 1.3 board, reflowed 07-SEP-17.

### Vertigo Mini
* 2001: [OPERATIONAL] Rev 1.0, hand soldered August 2017.
    In use for firmware dev.

## Hardware Changelog

* 1.0: 
    * Initial version.
    * MPU-9150 footprint used instead of MPU-9250
    * Immediately retired.
* 1.1:
    * Dropped helical onboard GPS antenna in favour of SMA with circuitry for active antenna.
    * Added reverse polarity protection.
* 1.2: 
    * Dropped bluetooth.
    * Added user push-button.
    * Dropped extra mini-USB (always use MBED one).
    * Added CHARGE LED for LiPo charger & disconnected CHARGE_STAT from MBED.
    * Removed duplicated PROG resistor (R4/R5).
* 1.3:
    * Baro pressure moved to separate SPI periph.
    * Fixed Vusb detect for disabling boost reg.
    * Added Test Points.
    * Added RESET line for GPS.
    * Added SHDN line for MPL115.
    * Added EEPROM (I2C).
    * Switched to TPS61251 boost conv.

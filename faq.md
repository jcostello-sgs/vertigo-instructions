# VertigoIMU Frequently Asked Questions

_A compact 11dof inertial datalogger with AHRS_

[Home](index.md)

## Powering Vertigo

### Can I use a different battery with VertigoIMU? ###

You must use a 1S (3.7V) lithium polymer (LiPo) or lithium ion (Li-Ion) battery
with Vertigo. We recommend a capacity of at least 800mAh.

### How long does Vertigo take to charge? ####

Using the supplied battery, expect a charge time of around 8 hours.

### How long does Vertigo run from its battery? ###

Using the supplied battery, expect run time of around 3 hours. For this reason,
it's best to power down Vertigo when you're not using it.

## Using Vertigo

### Which SD card should I use with Vertigo? ###

It is best to use the supplied SD card. If you want a spare, make sure that it
is no larger than 32GB, is class 10 or better, and is FAT32 formatted.

### Do I have to use the GPS? ###

No, absolutely not. Just begin data logging without attaching the GPS antenna.
Ignore the GPS readings in the log file (they will be all zero).

### How long does Vertigo take to get a GPS lock? ###

Providing the GPS antenna has a clear view of the sky, Vertigo should acquire a
GPS lock within 3 minutes.

### How many log files can I create on the SD card? ###

A maximum of 256 log files are supported (from `vtg_log0.csv` to
`vtg_log255.csv`).
If this is exceeded, the oldest will be overwritten first.

## Common Problems 

### When I power up Vertigo, all 4 LEDs flash once per second. ### 

This is the low battery warning. Please [charge Vertigo](usage.md).

### When I power up Vertigo, LED1 and LED4 flash fast alternately. ###

This is the error sequence, it means something is preventing Vertigo from
starting normally. Please check the troubleshooting section [here](usage.md).

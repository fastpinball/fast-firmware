# FAST Pinball Firmware

This repo contains publicly available firmware for FAST Pinball hardware. Instructions
for updating your firmware, and details about the various versions and features, are
available at [fastpinball.com/firmware](https://fastpinball.com/firmware/).

Firmware files in this repo:

## Controllers

* FP-CPU-2000 (FAST Neuron Controller)
* FP-CPU-003 (FAST Nano Controller)

## Expansion Boards

* FP-EXP-0051
* FP-EXP-0061
* FP-EXP-0071
* FP-EXP-0081
* FP-EXP-0091
* FP-EXP-1313

### Expansion Board Release Notes

#### `0.44` March 13, 2025

* Bug fix: Binary commands weren't working for mapped LEDs

#### `0.40` February 16, 2025

* Feature update: ER: command for configuring LED output ports

#### `0.38` January 25, 2025

* Bug fix: Motor outputs using hardware PWM now match software PWM

#### `0.37` January 22, 2025

* Feature update: Added support for 0051 Expansion

#### `0.36` October 31, 2024

* Feature update: New commands for RGBW serial LEDs

#### `0.32` October 1, 2024

* Bug fix: Unified code for newer versions of Neuron controller

#### `0.30` September 20, 2024

* Feature update: Added support for 0061 Expansion

#### `0.23` May 14, 2024

* Feature update: Added support for 1313 Expansion

#### `0.20` February 29, 2024

* Bug fix: increased RP2040 clock delay for more reliable startup

#### `0.12` August 17, 2023

* Bug fix: LED ports 5-8 didn't work on FP-EXP-0081 due to a typo

#### `0.11` August 16, 2023

* Bug fix: breakout board `ID:` responses
* Bug fix: `BR:` command

#### `0.10` August 7, 2023

* Early WIP EXP show scripting (`ES:`, `TS:` commands)
* Early WIP LED block support (`ER:` command)

#### `0.9` May 9, 2023

* Bug fix: `EM:` command
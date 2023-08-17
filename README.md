# FAST Pinball Firmware

This repo contains publicly available firmware for FAST Pinball hardware. Instructions
for updating your firmware, and details about the various versions and features, are
available at [fastpinball.com/firmware](https://fastpinball.com/firmware/).

Firmware files in this repo:

## Controllers

* FP-CPU-2000 (FAST Neuron Controller)
* FP-CPU-003 (FAST Nano Controller)

## Expansion Boards

* FP-EXP-0071
* FP-EXP-0081
* FP-EXP-0091

### Expansion Board Release Notes

#### `0.12` August 19, 2023

* Bug fix: LED ports 5-8 didn't work on FP-EXP-0081 due to a typo

#### `0.11` August 18, 2023

* Bug fix: breakout board `ID:` responses
* Bug fix: `BR:` command

#### `0.10` August 7, 2023

* Early WIP EXP show scripting (`ES:`, `TS:` commands)
* Early WIP LED block support (`ER:` command)

#### `0.9` May 9, 2023

* Bug fix: `EM:` command
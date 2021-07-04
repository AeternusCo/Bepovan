# Bepovan

![Image of Bepovan by pockets](/.github/bepovan.jpg)

> Photo credit: pockets#0042 from the 40% Keyboards Discord

## Introduction

Project Page: [Bepovan](https://github.com/AeternusCo/Bepovan)

This is the Bepovan case designed by Taylor (KnoblesseOblige) from Aeternus Company.
It is inspired by Bepo's (a user of the 40% Keyboards Discord) use of TFGH as their arrow keys.
It breaks out the TFGH as an emphasis to the keys themselves.
The other rows are shifted to accomodate and make things look aesthetically pleasing.

## Project Structure

Please note that PCB files are not currently available. They will be made available at a later date. Please check [Aeternus](https://store.aeternus.co) for Bepovan PCB availability in the meantime.

- case: Case files
  - stl: Files ready for 3d printing
  - step: Files ready for CNC manufacturing
  - dxf: Files ready for laser cutting
  - pdf: Files to accompany STEP files for CNC manufacturing
- pcb: PCB files

## Features

- Top mount plate (full, or half)
- Integrated MCU PCB with ESD production and a USB-C port
- Split space or 6.25u spacebar bottom row
- Separated TFGH cluster for "ergonomics"

## Hardware

Hardware can probably be sourced from elsewhere, McMaster-Carr links are provided for convenience.

Location       | Specifications | Link
-------------- | -------------- | ----
Plate to Top   | 4x M2x6mm      | https://www.mcmaster.com/catalog/91292A831
Bottom to Top  | 4x M2x10mm     | https://www.mcmaster.com/catalog/91292A833

## Firmware

The Bepovan firmware is not currently merged into main QMK. Please use our fork until then.

The Bepovan VIA config is not currently merged into main VIA. Please use our files until then.

QMK: [AeternusCo/qmk_firmware](https://github.com/aeternusco/qmk_firmware/tree/bepovan)

VIA: [Bepovan_VIA.zip](https://cdn.discordapp.com/attachments/784202611313868840/861264878644101130/Bepovan_VIA.zip)

## License

All files are licensed under CERN-OHL-P v2.

See [LICENSE](/LICENSE.md) file for more details.

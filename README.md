# Binary_Clock

## What is it
This project is about building and programming a binary clock. Including a mode for setting the time, a stop watch and a sleep mode.

The binary clock is built on a custom made PCB. The time is displayed in binary using LEDs, with the control logic running on a microcontroller.

## Hardware

- __Custom PCB:__ Designed from scratch on a copper board
- __Design files:__ KiCad project included in this repository
- __Microcontroller:__ ATMEGA48
- __Not runnable locally:__ The code targets this specific custom board and cannot run on standard hardware.


## Contents

| Folder   | Description                            |
| -------- | -------------------------------------- |
| [kiCad/] | KiCad project (schematic + PCB layout) |
| [src/]   | Microcontroller code                   |
| [other/] | Photos, schematics, notes              |

## How it works

The clock is driven by a quartz crystal for accurate timekeeping. It can be set via UART and additionally features a built-in stopwatch.


## What i learned

- Designing a PCB from schematic to finished board (KiCad)
- Soldering and hardware prototyping
- Programming a microcontroller for physical device
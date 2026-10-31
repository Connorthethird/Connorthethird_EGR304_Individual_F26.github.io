
---
layout: default
title: Bill of Materials
---

# Bill of Materials

**Connor Erwin | EGR 304 | Team 101**

## Project Overview

This Bill of Materials documents the weight-measurement subsystem for Team 101's Automatic Pet Food Dispenser. It includes parts from the team hardware order and Peralta 109.

## Component Bill of Materials

| Reference | Qty | Component / Value | Footprint | Source |
|---|---:|---|---|---|
| C1 | 1 | 0.33 µF, 50 V capacitor | 0805 SMD | Peralta 109 |
| C2, C3, C5, C6 | 4 | 0.1 µF, 50 V capacitors | 0805 SMD | Peralta 109 |
| D1 | 1 | Debug LED | 5 mm THT | Peralta 109 |
| F1 | 1 | MF-R050 resettable fuse | Radial THT, verify | Peralta 109 |
| J1 | 1 | DC barrel jack | Horizontal THT | Peralta 109 |
| J2 | 1 | 4-pin load-cell header | 2.54 mm THT | Peralta 109 |
| J3 | 1 | 8-pin team header | 2.54 mm THT | Peralta 109 |
| R1, R2, R4–R7, R9 | 7 | 10 kΩ, 0.25 W, 1% | 0805 SMD | Peralta 109 |
| R3, R8 | 2 | 1 kΩ, 0.25 W, 1% | 0805 SMD | Peralta 109 |
| SW1 | 1 | Momentary push button | 6 mm THT | Peralta 109 |
| TP1–TP3 | 3 | PCB test points | THT test pads | Peralta 109 |
| U1 | 1 | LM7805 / L7805CV regulator | TO-220-3 | Team order |
| U2 | 1 | MCP6004 quad op-amp | DIP-14 | Team order |
| U4 | 1 | PIC18F57Q43 Curiosity Nano | Development board | Previously supplied / verify |
| External sensor | 1 | SparkFun TAL220B, 5 kg load cell | External assembly | Team order |

**Total:** 26 schematic components plus the external load cell.

## Purchasing and Inventory

Major selected components are covered by the team's purchase request. Other components are available through Peralta 109. The complete BOM includes both purchased and lab-stock items.

## Engineering Notes

- R2's KiCad value and several resistor footprint fields need correction in the source schematic.
- Final footprints must be checked against physical components.
- Fuse current rating, regulator heating, and Curiosity Nano VTG/VOFF power configuration require verification.
- Prices and exact manufacturer part numbers remain to be confirmed for lab-stock items.


---
title: Power Budget
---

# Power Budget

**Connor Erwin | EGR 304 | Team 101**

## Overview

This power budget estimates the electrical requirements of the weight-sensing subsystem for Team 101's Automatic Pet Food Dispenser.

The subsystem uses a TAL220B load cell, an MCP6004 quad operational amplifier, a PIC18F57Q43 Curiosity Nano, and an L7805CV 5 V linear regulator.

## Component Power Requirements

| Component | Supply | Qty | Current Used in Budget | Notes |
|---|---:|---:|---:|---|
| PIC18F57Q43 Curiosity Nano | 5 V | 1 | 50 mA | Provisional design allowance |
| MCP6004 quad op-amp | 5 V | 1 | 0.68 mA | Four amplifiers, maximum quiescent current |
| TAL220B 5 kg load cell | 5 V | 1 | 5.05 mA | Based on minimum bridge input resistance of 990 ohms |
| Debug LED | 5 V | 1 | 3 mA | Operating estimate |
| Button pull-up | 5 V | 1 | 0.5 mA | Maximum when button is pressed |

## Power Calculations

Estimated budget current:

**59.23 mA**

With a 25% design margin:

**74.04 mA**

Estimated 5 V load power with margin:

**0.370 W**

Estimated LM7805 regulator heat at this design current:

**0.296 W**, excluding regulator quiescent current.

These are preliminary design-budget calculations, not experimentally measured maximum currents.

## Regulator and Supply

- Input supply: 9 V DC
- Regulated output: 5 V DC
- Regulator: L7805CV
- Current safety margin: 25%
- Regulator thermal performance and external power configuration require validation.

## Verification and Limitations

The PIC current allowance depends on firmware, clock frequency, active peripherals, and debugger operation. The MCP6004 value represents quiescent current rather than all possible output loading. Actual LED current depends on its forward voltage and series resistance.

Curiosity Nano VTG/VOFF connections must be verified before applying external power.

## Supporting Documentation

See the uploaded Connor power budget workbook for calculations, component assumptions, and datasheet sources.


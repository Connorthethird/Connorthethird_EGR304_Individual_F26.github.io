# Connor Erwin — Individual Datasheet

## Automatic Pet Food Dispenser

**Team 101 | EGR 304 | Arizona State University**

---

## Introduction

Welcome to my EGR 304 Individual Datasheet website. This website documents my engineering design process, component selection, hardware development, testing, and technical contributions to Team 101's Automatic Pet Food Dispenser project.

The website serves as a technical record of my subsystem's development throughout the semester, including design decisions, schematics, component specifications, power requirements, and supporting documentation.

## Project Summary

Team 101 is developing an **Automatic Pet Food Dispenser**, an embedded system designed to automate and monitor the process of dispensing pet food.

The system integrates multiple electronic and mechanical subsystems to detect operating conditions, dispense food, and measure the amount delivered.

The team project includes:

- **Input and Sensor Subsystem (Gary):** Provides input and sensing functionality for system operation.
- **Optical Sensor Subsystem (Caleb):** Provides optical sensing information for system monitoring.
- **Weight Measurement Subsystem (Connor):** Measures food weight using a load cell and signal-conditioning circuitry.
- **Motor Driver Subsystem (Daksh):** Controls the motor responsible for dispensing food.

These subsystems communicate through the team's electrical interfaces and microcontroller-based control architecture.

## My Contribution

My individual responsibility is the **Weight Measurement Subsystem**, which provides feedback about the amount of food dispensed.

The subsystem uses a strain-gauge load cell to detect weight changes. Because the load cell produces a small electrical signal, an MCP6004 operational amplifier circuit conditions the sensor output before it is measured by the PIC18F57Q43 Curiosity Nano microcontroller.

My responsibilities include designing and documenting:

- Load-cell sensor integration and signal conditioning.
- Microcontroller interfacing and analog-to-digital conversion.
- Voltage regulation and electrical protection.
- Debugging circuits, including an LED, push button, and test points.
- Electrical connections between my subsystem and the other team members' systems.
- Component selection, bill of materials, hardware ordering, and power-budget analysis.
- Schematic design, testing, and subsystem integration.

## Individual Design Documentation

The following sections document my engineering work:

- **Block Diagram:** Subsystem architecture and electrical interfaces.
- **Component Selection:** Evaluation and selection of major hardware components.
- **Bill of Materials:** Components, quantities, footprints, and procurement information.
- **Schematic:** Electrical circuit design and component connections.
- **Power Budget:** Estimated electrical current and power requirements.
- **Appendix:** Additional supporting documentation and technical resources.

This datasheet will be updated throughout the semester as design validation, testing, and integration progress.

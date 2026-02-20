# R–2R Ladder DAC using Two-Stage Operational Amplifier (gpdk180)

## Overview

Designed and simulated a 4-bit R–2R Ladder Digital-to-Analog Converter using a custom two-stage CMOS operational amplifier in Cadence Virtuoso (gpdk180 technology).
The project demonstrates digital-to-analog conversion using matched resistor networks and validates linearity through transient analysis.
---
## Objectives

- Design a two-stage differential CMOS Op-Amp
- Implement a 4-bit R–2R ladder network
- Integrate ladder with Op-Amp for analog output generation
- Verify DAC functionality using transient simulation

---

## Tools \& Technology

- Cadence Virtuoso
- gpdk180 Technology
- Analog CMOS Design
- ADE L (Transient Analysis)

---

## Design Details

### 1. Two-Stage CMOS Op-Amp

- Differential input stage
- Current mirror load
- Second gain stage
- Designed for 1.8V supply

### 2.  4-bit R–2R Ladder Network

- Uses only R and 2R resistor values
- Digital input: 1.8V logic
- Output taken through Op-Amp for scaling and buffering
---

## Simulation Setup

- Supply Voltage: 1.8V
- Transient Stop Time: 800ns
- Bit pattern applied sequentially
- Output verified for stepwise linear increase
---

## Results

- Verified monotonic step output
- Observed correct binary-weighted analog output
- Successful digital-to-analog conversion
---

## Key Learning Outcomes

- Practical CMOS analog circuit design
- R–2R ladder architecture implementation
- Op-Amp compensation basics
- Transient simulation and waveform verification
- gpdk180 device-level modeling
---

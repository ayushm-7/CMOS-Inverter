# CMOS-Inverter

## Overview

This project presents the design, simulation, and performance characterization of a CMOS inverter using **Predictive Technology Model (PTM) 180 nm BSIM Level-49 MOSFET models** in LTspice. The inverter was analyzed to evaluate its switching characteristics, propagation delay, power consumption, and the effect of output load capacitance.

---

## Objectives

- Design a CMOS inverter using PTM 180 nm MOSFET models.
- Analyze the Voltage Transfer Characteristic (VTC).
- Measure propagation delay (tPHL and tPLH).
- Evaluate average power consumption.
- Compare NMOS and PMOS power dissipation.
- Study the impact of output load capacitance on delay and power.

---

## Circuit Specifications

| Parameter | Value |
|-----------|-------|
| Technology | PTM 180 nm |
| Simulator | LTspice |
| MOSFET Model | BSIM Level-49 |
| Supply Voltage | 2 V |
| NMOS Size | W/L = 360 nm / 180 nm |
| PMOS Size | W/L = 900 nm / 180 nm |
| Load Capacitor | 10 fF, 50 fF, 100 fF |

---

## Simulations Performed

- DC Sweep Analysis (Voltage Transfer Characteristic)
- Transient Analysis
- Propagation Delay Measurement
- Average Power Analysis
- NMOS & PMOS Individual Power Dissipation
- Load Capacitance Analysis

---

## Results

### Average Power Consumption

| Load Capacitance | NMOS Power | PMOS Power | Total MOS Power | Power from VDD |
|-----------------:|-----------:|-----------:|----------------:|---------------:|
| 10 fF | 3.6581 µW | 3.8367 µW | 7.4948 µW | 7.4840 µW |
| 50 fF | 6.7653 µW | 6.9127 µW | 13.6780 µW | 13.6100 µW |
| 100 fF | 11.3550 µW | 11.4940 µW | 22.8490 µW | 22.7470 µW |

---

### Key Observations

- The CMOS inverter exhibits rail-to-rail voltage swing with low static power consumption.
- Propagation delay increases with increasing load capacitance.
- Dynamic power consumption increases approximately linearly with load capacitance.
- The sum of NMOS and PMOS power closely matches the power supplied by VDD, validating the simulation results.

---

## Tools Used

- LTspice
- Predictive Technology Model (PTM) 180 nm
- BSIM Level-49 MOSFET Models

---

## Repository Contents

- CMOS Inverter LTspice Schematic (.asc)
- PTM 180 nm MOSFET Models
- Simulation Report (PDF)
- Simulation Waveforms
- Performance Analysis

---

## Future Scope

- Noise Margin Analysis
- Power-Delay Product (PDP)
- Temperature Analysis
- Supply Voltage Scaling
- CMOS Full Adder Design using PTM 180 nm

---

## Author

**Ayush Mohanty**

Electronics & Instrumentation Engineering  
NIT Rourkela

# Design-and-Verification-of-a-6T-SRAM-Cell-Using-Cadence-Tools
# 6T SRAM Cell Design and Verification using Cadence Virtuoso

## Overview

This project presents the design, layout, simulation, and physical verification of a **6-Transistor (6T) Static Random Access Memory (SRAM) cell** using the **Cadence Virtuoso** design environment. The SRAM cell is implemented using CMOS technology and verified through schematic simulations, layout validation, and post-layout analysis.

The project demonstrates the complete VLSI design flow, from circuit implementation to physical verification, ensuring the SRAM cell meets functional and design-rule requirements.

---

## Features

* CMOS-based 6T SRAM cell design
* Schematic implementation in Cadence Virtuoso
* Custom layout design
* Read '0' and Read '1' operation verification
* Transient waveform analysis
* Design Rule Check (DRC)
* Layout Versus Schematic (LVS) verification
* Parasitic extraction (RCX)
* Average power consumption analysis

---

## SRAM Cell Architecture

The 6T SRAM cell consists of:

* Two cross-coupled CMOS inverters for data storage
* Two NMOS access transistors controlled by the Word Line (WL)
* Differential Bit Lines (BL and BLB) for read and write operations

---

## Design Flow

1. Design the 6T SRAM schematic.
2. Perform functional simulations.
3. Create the physical layout.
4. Run DRC to verify layout design rules.
5. Perform LVS to ensure layout matches the schematic.
6. Execute RCX for parasitic extraction.
7. Simulate the extracted layout.
8. Analyze transient waveforms and power consumption.

---

## Verification

### Functional Verification

The SRAM cell was tested for:

* Read '0' operation
* Read '1' operation

Simulation results confirm proper voltage development on:

* Bit Line (BL)
* Bit Line Bar (BLB)

during both read operations.

---

## Physical Verification

The following verification steps were successfully completed:

* **DRC (Design Rule Check)** – No design rule violations.
* **LVS (Layout Versus Schematic)** – Layout matches the schematic.
* **RCX (Parasitic Extraction)** – Post-layout parasitic effects extracted for accurate simulation.

---

## Power Analysis

Average power consumption obtained from transient simulation:

**Average Power:** **486.6 nW**

Power analysis confirms that the SRAM cell operates with low power while maintaining correct functionality.

---

## Project Structure

```text
├── Schematic/
│   ├── 6T_SRAM_Schematic
│
├── Layout/
│   ├── 6T_SRAM_Layout
│
├── Simulation/
│   ├── Read_0
│   ├── Read_1
│   ├── Waveforms
│
├── Verification/
│   ├── DRC
│   ├── LVS
│   ├── RCX
│
├── Power_Analysis/
│
├── Report.pdf
│
└── README.md
```

---

## Tools Used

* Cadence Virtuoso
* Cadence Spectre Simulator
* CMOS Technology Library

---

## Results

* Successful implementation of a CMOS 6T SRAM cell
* Correct read functionality verified through simulation
* Clean DRC and LVS reports
* Accurate post-layout verification using RCX
* Average power consumption of **486.6 nW**
* Functional and layout-correct SRAM design suitable for VLSI applications

---

## Applications

* On-chip cache memory
* Embedded memory systems
* Microprocessors
* System-on-Chip (SoC) designs
* Low-power VLSI circuits

---

## License

This project is intended for educational and research purposes.
.

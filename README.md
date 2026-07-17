# Analog IC Design: Operational Amplifier (Op-Amp) & Comparator

This repository contains the design, simulation, and calculation of a Two-Stage Operational Amplifier (Op-Amp) and Comparator as part of the Analog IC Design course at Hanoi University of Science and Technology (HUST).

## 📂 Project Structure

This project includes the following main deliverables:

1. **Simulation File (`Draft9 (1).asc`)**: 
   - The complete schematic and simulation testbench created using **LTspice**.
   - Includes **DC analysis** (for operating points) and **AC analysis** (to verify gain, bandwidth, and phase margin).

2. **Design & Calculation Document (`ThietKeOpAmp_ICTT.pptx`)**:
   - Detailed presentation outlining the design methodology, hand calculations, transistor sizing, and simulation results.

---

## 🚀 Key Specifications & Features Covered
- **Architecture:** Two-Stage CMOS Operational Amplifier & Comparator.
- **Tools Used:** LTspice for circuit simulation and verification.
- **Analysis Types:** 
  - **DC Sweep / Operating Point Analysis:** To ensure all transistors operate in the saturation region.
  - **AC Analysis (Small-signal):** To measure Open-Loop Gain, Unity Gain Bandwidth (UGB), and Phase Margin (PM).

---

## 🛠️ How to Run the Simulation
1. Download and install [LTspice](https://www.analog.com/en/resources/design-tools-and-calculators/ltspice-simulator.html).
2. Download both the simulation file `Draft9 (1).asc` and any required semiconductor library/models from this repository (if applicable).
3. Open `Draft9 (1).asc` in LTspice and run the simulation (Press `F5` or click the "Run" icon) to view the AC/DC frequency response and waveforms.

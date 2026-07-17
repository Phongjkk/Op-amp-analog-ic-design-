# Analog IC Design: Operational Amplifier (Op-Amp) & Comparator

This repository contains the design, simulation, and calculation of a Two-Stage Operational Amplifier (Op-Amp) as part of the Analog IC Design course at Hanoi University of Science and Technology (HUST).

## 📂 Project Structure

This project includes the following main deliverables:

1. **Simulation File (`Draft9 (1).asc`)**: 
   - The main schematic and simulation testbench created using **LTspice**.
   - Includes **DC analysis** (for operating points) and **AC analysis** (to verify gain, bandwidth, and phase margin).

2. **Setup & Libraries (`01_LTspice Install/`)**:
   - This folder contains the LTspice installer and the required semiconductor/technology library files.
   - Essential for running the simulation without any "missing model" errors.

3. **Design & Calculation Document (`ThietKeOpAmp_ICTT.pptx`)**:
   - Detailed presentation outlining the design methodology, hand calculations, transistor sizing, and simulation results.

---

## 🚀 Key Specifications & Features Covered
- **Architecture:** Two-Stage CMOS Operational Amplifier.
- **Tools Used:** LTspice for circuit simulation and verification.
- **Analysis Types:** 
  - **DC Sweep / Operating Point Analysis:** To ensure all transistors operate in the saturation region.
  - **AC Analysis (Small-signal):** To measure Open-Loop Gain, Unity Gain Bandwidth (UGB), and Phase Margin (PM).

---

## 🛠️ How to Run the Simulation

To run the simulation successfully, you need to use the library files provided in the setup folder:

1. **Install LTspice:**
   - If you haven't installed LTspice yet, use the installer inside the `01_LTspice Install/` folder.

2. **Set up the Library:**
   - Copy the library files (e.g., `.lib`, `.model` or `.include` files) from `01_LTspice Install/` and place them in the **same folder** as your simulation file `Draft9 (1).asc`.

3. **Open & Run:**
   - Open `Draft9 (1).asc` in LTspice.
   - Press **Run** (the running man icon or `F5`) to start the simulation and view the AC/DC frequency response and waveforms.

# Turbofan Performance Analysis & Thermodynamic Modeling

## Overview
This repository contains a MATLAB-based simulation and analytical report on the performance of a **Low-Bypass Turbofan Engine equipped with an Afterburner**. The project evaluates the engine's operational efficiency and thermodynamic losses across varying flight regimes, with a specific focus on high-altitude performance constraints.

## Project Objectives
* **Parametric Analysis:** Investigate the effect of Bypass Ratio (BPR) on Thrust, TSFC, and Propulsive Efficiency.
* **Environmental Impact:** Compare performance between ideal flight conditions and high-altitude (low-density) environments.
* **Thermal Analysis:** Quantify entropy generation ($ds$) across individual engine components to identify efficiency bottlenecks.
* **Fluid Dynamics:** Model the Area-Mach relationship in the core nozzle to evaluate exhaust flow behavior.

## Repository Structure
* `/MATLAB_Scripts`: Contains scripts for "Ideal Cruise" and "High-Altitude (Ladakh)" scenarios.
* `/Results`: Graphical plots including Entropy Generation, Pressure Ratios, and Efficiency vs. BPR.
* `/Report`: Final technical report detailing the thermal and fluid analysis findings.

## Technical Specifications
The simulation utilizes the following parameters (representative of fighter-class engines):
- **Core Mass Flow ($m_{dot}$):** Adjusted for altitude-dependent air density.
- **Component Efficiencies:** Modeled for Diffuser ($\eta_d$), Compressor ($\eta_c$), Burner ($\eta_b$), and Turbine ($\eta_t$).
- **Variables:** $M_0$ (Flight Mach Number), $T_0$ (Ambient Temperature), and $P_0$ (Ambient Pressure).

## Key Findings
1. **Entropy Generation:** The combustor and turbine were identified as the primary sources of thermodynamic irreversibility.
2. **Altitude Sensitivity:** Significant reduction in net thrust was observed in low-density environments, necessitating specific tuning of the fuel-air ratio.
3. **Optimization:** Identified the optimal BPR range for maintaining high specific thrust while maximizing propulsive efficiency.

## How to Run
1. Ensure MATLAB is installed.
2. Open `jet_engine_analysis.m`.
3. Run the script to generate performance characteristic curves and entropy plots.

## License
This project is for educational and research purposes.

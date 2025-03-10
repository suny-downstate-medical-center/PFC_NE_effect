# PFC_NE_effect

## Overview
**PFC_NE_effect** is a computational neuroscience project investigating the roles of **intratelencephalic (IT) neurons** and **pyramidal tract (PT) neurons** in the **prefrontal cortex (PFC)**. The project explores how IT and PT neurons influence **network dynamics, oscillatory behavior, and information processing** in both control and pathological conditions (e.g., Parkinson’s disease).  

The study aims to:
- Compare the effects of IT and PT neuron activity in normal and disease states.
- Investigate **cortical oscillatory patterns, and network stability**.
- Analyze the effects of **neuromodulation (e.g., norepinephrine, NE)** on IT and PT neurons.

## Research Objectives
- **PFC_IT_effect**:
  - Examine the role of IT neurons in **beta-gamma coupling, modulation index**.
  - Tune IT model parameters to match the **F-I curve** for experimental data:
    - **Baseline (no NE applied)**
    - **NE applied condition**
  - Investigate IT neuron imbalances in Parkinson’s disease and their impact on **cortical excitability**.

- **PFC_PT_effect**:
  - Analyze PT neuron activity in **normal and Parkinsonian conditions**.
  - Explore how PT neurons contribute to **corticospinal and corticostriatal interactions**.
  - Investigate PT neuron intrinsic resonance and **bistable dynamics (e.g., transitions between walking and running)**.

## Methodology
This project employs:
- **Computational models using NetPyNE** for network simulations.
- **LFP and spike data analysis** to measure power spectral density, modulation index.
- **F-I curve tuning** to calibrate IT and PT neuron responses to experimental data.
- **Comparison of control and Parkinsonian conditions** to understand IT and PT contributions to disease-related network changes.

## Requirements
To run the simulations and analyses, you need:
- Python 3.8+
- [NetPyNE](https://www.netpyne.org/)
- NumPy, SciPy, Matplotlib, and Pandas
- Additional libraries for signal processing:
  ```sh
  pip install numpy scipy matplotlib pandas netpyne neo elephant

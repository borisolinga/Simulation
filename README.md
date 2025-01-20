# Optimization of LoRa Transmission Parameters

This code aims to optimize LoRa transmission parameters for an autonomous water sensor powered by a capacitor. The objective is to analyze energy consumption and select the most efficient transmission configurations based on the available energy.

## Code Overview

The system operates within a capacitor voltage range of **1.8V to 3.3V**, which defines the operational window for both the LoRa module and the water sensor. By measuring current consumption at different transmission settings, the optimal parameters are identified.

## Code Contents

- **Simulation1.ipynb** – Jupyter Notebook containing Python code for data analysis and visualization.
- **README.md** – Code documentation.

## Methodology

The optimization process consists of the following steps:

1. Measuring current consumption for different LoRa transmission configurations.
2. Comparing energy consumption with the available energy of the capacitor.
3. Evaluating two bandwidth configurations: **125 kHz** and **250 kHz**, both with a fixed Spreading Factor of 7.
4. Selecting optimal parameters based on energy efficiency.

## Key Findings

- **125 kHz Bandwidth:**
  - A limited number of configurations meet the energy constraints.
  - Only specific transmission power levels are suitable.

- **250 kHz Bandwidth:**
  - More configurations meet the energy constraints.
  
## Usage Instructions

### Prerequisites

Ensure that you have the following installed:

- Python (≥3.7)
- Jupyter Notebook
- Required Python libraries:

  ```bash
  pip install numpy pandas matplotlib

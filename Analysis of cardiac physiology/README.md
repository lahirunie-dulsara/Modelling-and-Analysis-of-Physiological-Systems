
# CircAdapt Simulation: Cardiac Rhythm Analysis

This project uses the **CircAdapt** cardiovascular simulation software to model and compare **normal cardiac rhythm** and **cardiac rhythm during aortic valve stenosis**. The goal is to analyze physiological changes using simulation outputs and interpret them using concepts like the **Wiggers diagram**.

---

## Objective

- Simulate **normal** cardiac rhythm.
- Simulate **aortic valve stenosis**.
- Analyze and compare cardiovascular behavior under both conditions.
- Visualize and interpret results through relevant plots (e.g., pressure-volume loops, ventricular pressure curves).

---

## Software Download

Download the **CircAdapt Simulator** (v1.1.0 or #2) from the official website:  
🔗 [https://www.circadapt.org/download-links/](https://www.circadapt.org/download-links/)

> Note: Ensure MATLAB (2020 or later) is installed and properly configured as CircAdapt runs within the MATLAB environment.

---

## How to Run Simulations

1. **Install CircAdapt**  
   Unzip and set up the CircAdapt folder in your MATLAB working directory.

2. **Launch CircAdapt GUI**  
   Run `CircAdapt.m` to launch the graphical user interface.

3. **Load Simulation Models**  
   - For normal rhythm: Load default or baseline model.
   - For aortic valve stenosis: Modify the model settings (reduce aortic valve area/increase resistance).

4. **Run Simulations and Export Data**  
   Use the GUI to simulate and export results such as:
   - Left ventricular pressure
   - Aortic pressure
   - Volume changes
   - Pressure-volume loops

---



## Reference Material

- CircAdapt Simulator Documentation  
- [Wiggers Diagram](https://www.cvphysiology.com/Hemodynamics/H016) – Reference for understanding pressure-volume relationships and cardiac phases  
- Relevant literature on Aortic Valve Stenosis (see report for citations)

---

## Report Contents

- Explanation of simulation parameters and model assumptions
- Plots comparing normal and stenotic conditions
- Discussion on:
  - Pressure changes
  - Stroke volume and cardiac output
  - Changes in the Wiggers diagram elements

---

## License & Acknowledgements

This simulation is built using the **CircAdapt** software developed by Maastricht University.  
Please refer to their [Terms of Use](https://www.circadapt.org/) for academic usage and licensing.

---




# Branched Cylinder Modelling - Dendritic Tree Approximations

This repository contains the MATLAB scripts and explanations for **Assignment 2** of BM2101: Analysis of Physiological Systems. The goal of this assignment is to explore the time-independent electrical properties of single branched cables, which model passive electrical properties of axonal and dendritic trees.

## Overview

We model a **first-order branched cable**, focusing on steady-state membrane potentials in the parent and two daughter branches. Using electrotonic distance (`X = x/λc`), we derive and solve matrix equations describing the voltage distribution.

- `cable.m`: Defines the coefficient matrix **A** for the system.
- 
## Questions Addressed

1. **Theoretical derivation** of the solution from boundary and nodal constraints.
2. **Verification** that the matrix equation reproduces the correct system of equations.
3. **Solving** for coefficients of membrane potential using MATLAB.
4. **Plotting** the steady-state voltage profile in each branch.
5. **Interpretation** of the voltage gradient at the ends of daughter branches under different boundary conditions.
6. **Parametric variation** by changing diameters and analyzing effects on the voltage profile.


## Dependencies

- MATLAB (no additional toolboxes required)

## Notes

- The model is restricted to first-order branching but principles extend to higher-order trees.
- Terminal ends can be "killed" (voltage held at rest) or reflect modified current conditions.
- Voltage profiles vary depending on boundary conditions and branch diameters.

## License

This project is for academic purposes only and is shared under the [MIT License](LICENSE).


# Hodgkin-Huxley Model Simulation - Action Potential Dynamics

This repository contains MATLAB files and documentation for **Assignment 4** of *BM2102: Analysis of Physiological Systems*. The assignment simulates various physiological properties of action potentials using the classic **Hodgkin-Huxley equations**, as observed in the squid giant axon.

## Objective

To simulate and analyze the following features of action potential generation:
- Threshold behavior
- Absolute and relative refractoriness
- Repetitive firing activity
- Temperature dependence

## Repository Structure

- `hhconst.m`: Initializes Hodgkin-Huxley model parameters.
- `hhmplot.m`: Plots action potentials over time with given stimuli.
- `hhsplot.m`: Plots and returns integrals of sodium, potassium, and leakage currents.

## Simulation Details

### 1. Threshold Detection
Estimates the minimal current amplitude to trigger an action potential using binary search methods on `amp1`.

### 2. Refractoriness
Simulates two successive current pulses to identify:
- Absolute refractory period (no second AP regardless of stimulus)
- Relative refractory period (increased threshold for second AP)

### 3. Repetitive Activity
Uses long-duration stimuli to trigger multiple action potentials, analyzing the frequency and amplitude dependency on stimulus strength.

### 4. Temperature Dependence
Varies `tempc` to assess changes in action potential duration and amplitude, reflecting faster ionic kinetics at higher temperatures.

## How to Run

1. Open MATLAB and navigate to the project directory.
2. Run `hhconst` to load model constants.
3. Use `hhmplot(t0, tf, hold)` or `hhsplot(t0, tf)` with configured parameters (`amp1`, `width1`, `delay2`, etc.) to simulate and plot.
   
## Requirements

- MATLAB
- No additional toolboxes are necessary

## Notes

- Action potentials are modeled in a space-clamped axon (no spatial propagation).
- Model dynamics are based on the original 1952 parameters by Hodgkin and Huxley.

## License

This project is licensed under the [MIT License](LICENSE).


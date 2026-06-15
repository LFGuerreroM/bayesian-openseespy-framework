# Bayesian Framework for OpenSeesPy Integration

This repository contains the computational implementation accompanying the manuscript submitted to *MDPI Infrastructures*. The framework integrates probabilistic inversion and hierarchical calibration directly with deterministic structural finite element formulations.

## Repository Contents

*   **`01_benchmarks.ipynb`**: Contains the numerical verification phases including quadratic linear regression, a non-linear sinusoidal model, and the direct coupling verification of an OpenSeesPy planar frame model via custom PyTensor operators.
*   **`02_case_studies.ipynb`**: Contains the engineering validation applications, covering operational modal analysis for stiffness identification and an advanced Hierarchical Stochastic Model (HSM) for the non-linear constitutive calibration of Steel4 hysteretic material.

## Core Dependencies

To execute these notebooks, a Python 3.x environment with the following packages is required:
*   `pymc` (v5.x)
*   `pytensor`
*   `openseespy`
*   `numpy`
*   `scipy`
*   `matplotlib`

All notebooks are designed to be entirely self-contained; analytical and experimental datasets are embedded directly within the code cells to eliminate external file dependencies.

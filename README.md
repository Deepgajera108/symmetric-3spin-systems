# symmetric-3spin-systems

This repository contains a collection of Python notebooks for analyzing quantum systems using concurrence as a measure of entanglement. The analysis involves numerical simulations, heatmap visualizations, and parameter tuning for quantum Hamiltonians.
## Table of Contents
1. [Overview](#overview)
2. [Repository Structure](#repository-structure)


The project explores quantum systems using concurrence as a metric to understand entanglement properties. The notebooks provided perform the following tasks:

- Compute concurrence (`concur_fin`) from Hamiltonians.
- Generate and visualize heatmaps of concurrence as a function of quantum parameters (e.g., `j3` and `j4`).
- Analyze specific quantum systems (e.g., 3-spin systems or triangular lattices).

### Repository Structure
- `concurrence.ipynb`: Core notebook for computing concurrence (`concur_fin`) from quantum Hamiltonians. Includes optimization and numerical computations.
- `concurrenceplot.ipynb`: Notebook for generating heatmaps of concurrence (`concur_fin`) using varying parameters (`j3`, `j4`).
- `3spin.ipynb`: Analyzes 3-spin quantum systems and computes concurrence for specific configurations.
- `triangle.ipynb`: Investigates triangular quantum lattices and calculates entanglement metrics.

### Supporting Data:
- Include data files used by the notebooks (e.g., `updated_hamiltonian_results_j3_j4_vecs.csv`).

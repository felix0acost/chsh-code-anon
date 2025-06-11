# CHSH Quantum Game – Anonymous Submission

This repository contains the implementation of the optimal quantum strategy for the CHSH game using Qiskit.

## Contents

- `FixedTestCHSH.ipynb`: Jupyter notebook that builds the entangled quantum circuit, executes it on IBM Quantum hardware, and compares the experimental results with the expected theoretical probabilities.
- Utilities for data visualization and probability comparison.

## Description

The experiment prepares a Bell state and applies parametrized rotation gates \( R_y(\theta) \) and \( R_y(\phi) \) based on the input values (X, Y). The resulting output probabilities are compared against those obtained from the wavefunction of the theoretical model.

## Requirements

- Python 3.9+
- Qiskit
- matplotlib
- numpy

Install dependencies using:

```bash
pip install qiskit matplotlib numpy

# Test Suite for NN Surrogate B3LYP XC Funtional

## Workflow

1. Use Psi4 to calculate moleule of interest at B3LYP/aug-cc-pvtz level of theory, and project the converged density and XC energy density on a grid.
2. Calculate the MCSH convolutional descriptors.
3. Predict the energy with the model provided.

## Main functions

### psi4_generate_data_set.py


# Linear and Poly Model Likelihood

# Bayesian Analysis of Probabilistic Models - Exercise 7

This repository contains the notebook `S3E7_MML.ipynb`, which covers an exercise on using the Bayesian formalism to compare probabilistic models of varying complexity.

## Description

The notebook addresses the following points:

1. **Theoretical Framework**: 
   - Calculation of the log-marginal likelihood (*log-evidence*) using the Laplace approximation.
   - Discussion of the complexity penalty (Occam's Razor principle).

2. **Synthetic Data Generation**: 
   - Data generated from a linear model with Gaussian noise.

3. **Model Comparison**:
   - Linear model $M_1$: $y = \theta_0 + \theta_1 x$
   - 5th-degree polynomial model $M_2$: $y = \sum_{k=0}^5 \theta_k x^k$

4. **Evidence Analysis**:
   - Calculation and graphical representation of the evidence trend as the sample size $N$ increases.
   - Identification of the *Occam region* $N^*$, where the simpler model $M_1$ is preferred.

5. **Effect of Priors**:
   - Discussion on how the choice of a sparse prior (e.g., Laplace distribution) influences the comparison between models.

## Requirements

- Python 3.x
- Main libraries:
  - `numpy`
  - `matplotlib`
  - `scipy`

## Execution

To reproduce the analysis:

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
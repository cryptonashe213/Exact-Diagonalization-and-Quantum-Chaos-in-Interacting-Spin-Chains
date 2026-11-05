
# Exact Diagonalization and Quantum Chaos in Interacting Spin Chains

## Overview

This project explores the spectral properties of interacting quantum spin chains using exact diagonalization techniques.

The main objective is to develop a computational understanding of finite-dimensional quantum many-body systems and investigate the relationship between interactions, energy spectra, and quantum chaos.

The project combines theoretical quantum mechanics with numerical simulations implemented in Python.

## Physical Background

Interacting spin chains provide a useful framework for studying quantum many-body physics.

A representative model is the spin-1/2 XXZ Hamiltonian:

H = J Σᵢ (SᵢˣSᵢ₊₁ˣ + SᵢʸSᵢ₊₁ʸ)
    + Δ Σᵢ SᵢᶻSᵢ₊₁ᶻ

where:

- J is the exchange coupling.
- Δ is the interaction anisotropy.
- Sᵢ are spin-1/2 operators.

The spectrum and eigenstates of the Hamiltonian provide information about the underlying quantum dynamics.

## Objectives

- Understand the construction of quantum spin Hamiltonians.
- Apply exact diagonalization to finite quantum systems.
- Investigate energy spectra and eigenstates.
- Explore spectral signatures associated with quantum chaos.
- Develop numerical methods for quantum many-body physics.

## Computational Approach

The project uses Python and scientific computing libraries to construct and analyse finite-dimensional Hamiltonians.

Exact diagonalization provides access to eigenvalues and eigenvectors, allowing the investigation of spectral properties and their physical interpretation.

## Technologies

- Python
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook

## Repository Contents

The repository contains the Jupyter notebook with the theoretical discussion, numerical implementation, and analysis.

## Scope and Limitations

Exact diagonalization is limited by the exponential growth of the Hilbert-space dimension with system size.

The project focuses on finite-size systems and the interpretation of their numerical properties.

## Author

Rubén Orleans Aguilar

Physics Undergraduate  
University of Zaragoza

Research interests: Computational Physics, Quantum Many-Body Systems, and Scientific Computing.

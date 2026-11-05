# Many-Body Localization and Breakdown of ETH in a Disordered XXZ Chain

## Overview

This project explores the physics of interacting quantum many-body systems through numerical simulations of a disordered spin-1/2 XXZ chain.

The main objective is to investigate the emergence of many-body localization (MBL) and its relationship with the breakdown of the Eigenstate Thermalization Hypothesis (ETH).

The project is developed in Python using numerical methods and exact diagonalization techniques.

## Theoretical Background

The disordered XXZ Hamiltonian can be written as:

H = J Σᵢ (SᵢˣSᵢ₊₁ˣ + SᵢʸSᵢ₊₁ʸ) + Δ Σᵢ SᵢᶻSᵢ₊₁ᶻ + Σᵢ hᵢSᵢᶻ

where:

- J represents the spin-exchange coupling.
- Δ controls the interaction anisotropy.
- hᵢ represents the local random magnetic field.
- Sᵢ are spin-1/2 operators.

Disorder and interactions compete to produce different dynamical and spectral regimes.

## Objectives

- Study the spectral properties of interacting quantum spin chains.
- Explore the effects of disorder on quantum many-body systems.
- Investigate signatures of ergodic and localized behaviour.
- Understand the relationship between quantum chaos, thermalization and localization.

## Computational Methods

The project uses Python-based numerical simulations, with emphasis on:

- Hamiltonian construction.
- Exact diagonalization.
- Numerical analysis of quantum states and observables.
- Visualization and interpretation of simulation results.

## Technologies

Python · NumPy · SciPy · Matplotlib · Jupyter Notebook

## Project Structure

- `notebook.ipynb` — Numerical implementation and analysis.
- `figures/` — Selected figures generated from simulations.
- `requirements.txt` — Python dependencies.

## Future Work

Possible extensions include larger system sizes, finite-size scaling and additional diagnostics of many-body localization.

## Author

Rubén Orleans Aguilar  
Physics Undergraduate — University of Zaragoza

**Research interests:** Computational Physics, Quantum Many-Body Systems and Scientific Computing.

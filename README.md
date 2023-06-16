# Quantum ESPRESSO NEXAFS Workflow

This repository provides a comprehensive workflow for simulating Near Edge X-ray Absorption Fine Structure (NEXAFS) spectra using Density Functional Theory (DFT) as implemented in Quantum ESPRESSO. While the workflow is targeted towards modeling dopant distributions in conjugated polymers, it can be applied to any arbitrary molecular system. 

## Features

- **Explicit Installation in Google Colab**: We provide scripts for installing Quantum ESPRESSO in Google Colab environments, allowing users to easily leverage cloud compute resources.

- **Core Hole Pseudopotentials**: Detailed instructions are given for generating core hole pseudopotentials, a crucial step for accurate NEXAFS simulations.

- **Work Function Extraction**: Our workflow also includes procedures for extracting pseudopotential work functions, which are necessary for the XSpectra calculations in Quantum ESPRESSO.

- **NEXAFS Visualization**: We provide a utility for visualizing how the NEXAFS spectra should vary with molecular orientation relative to the X-ray polarization vector, within the uniaxial optical tensor approximation.

## Future Developments

- **Atom Selection for NEXAFS Simulation**: A future feature will enable users to select specific atoms over which to simulate spectra, sum these spectra, and reproduce the polarization-dependent NEXAFS for the given list of atoms.

- **KKCalc Implementation**: We plan to implement KKCalc, which will allow the resultant NEXAFS to be normalized to the bare atom scattering factors from the Henke Database and generate the real and imaginary portions of the optical constants. This is one of the direct inputs into CyRSoXS.

## Disclaimer

While this workflow aims to provide a practical approach to simulating NEXAFS, there are no guarantees of scientific accuracy. Please use the workflow responsibly and in conjunction with sound scientific judgment.

## Application

This workflow is particularly suited for research into conjugated polymers and their dopant distributions, providing valuable insight into their electronic structure and interactions. The simulations produced can be directly used for modeling resonant soft X-ray scattering, specifically with the NRSS package from NIST. 

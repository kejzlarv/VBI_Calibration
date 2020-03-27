# Supplementary data and code to "Variational Inference with Vine Copulas: An efficient Approach for Bayesian Computer Model Calibration" by Kejzlar and Maiti (2020)

This repository contains complete Python code to reproduce the simulation and calibration of the Liquid drop model (LDM) in "Variational Inference with Vine Copulas: An efficient Approach for Bayesian Computer Model Calibration."

## Content of jupyter notebooks with source code:
1. [Variational Bayesian calibration - Simulation and LDM](Variational_calibration.ipynb) - Self-sufficient notebook with the complete implementation of VBI. It contains source code for both the simulation and the LDM calibration applications. Sampling from posterior predictive distributions and least squares estimates for the LDM are also implemented here.
2. [MCMC based Bayesian calibration - Simulation](Scalability_plots.ipynb) - Self-sufficient notebok with implementation of MCMC based calibration under the simulation scenario.
3. [MSE and Memory profiles plots](MCMC_calibration.ipynb) - Contains source code for Fig.3 and Fig.6 from the manuscript.

## Content of supplementary files:
1. [AME2003 dataset](mass.mass03) - Raw dataset of experimental binding energies
2. [2500_2500_10_init.json](2500_2500_10_init.json), [5000_5000_10_init.json](5000_5000_10_init.json), [10000_10000_10_init.json](10000_10000_10_init.json), [144_81_3_init.json](144_81_3_init.json), [LDM_init.json](LDM_init.json) - files with innitializations for the VBI algorithm
3. [2500_2500_10.pickle](2500_2500_10.pickle), [5000_5000_10.pickle](5000_5000_10.pickle), [10000_10000_10.pickle](10000_10000_10.pickle), [144_81_3.pickle](144_81_3.pickle) - Generated data for the simulation scenario
4. [LDM_results](LDM_results), [Simulation_results](Simulation_results) - Precomputed results to reproduce all the figures and tables in "Variational Inference with Vine Copulas: An efficient Approach for Bayesian Computer Model Calibration" by Kejzlar and Maiti (2020)
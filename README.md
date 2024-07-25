# RSV Simulation Project

This repository contains Python code and data files for simulating the spread and impact of Respiratory Syncytial Virus (RSV) using a modified SIRS'I' model. The model aims to provide a simplified yet effective representation of RSV dynamics, with additional scenarios to explore the effects of COVID-like isolation measures and vaccination strategies.

## Table of Contents

- [Background](#background)
- [Model Description](#model-description)
- [Files Included](#files-included)


## Background

Respiratory Syncytial Virus (RSV) is a significant cause of respiratory infections in children. Understanding the population dynamics of RSV can help in developing effective public health strategies. This project implements an extended version of the SIRS'I' model to simulate RSV dynamics and incorporates scenarios such as COVID-like isolation measures and infant vaccination.

## Model Description

The mathematical model involves the following compartments:
- **Susceptible (S)**
- **Infected (I)**
- **Recovered (R)**
- **Re-Susceptible (S' or s)**
- **Reinfected (I' or i)**

Differential equations are solved using Python, and the results are visualized to understand the impact of various parameters on the spread of RSV.

## Files Included

- `data/`: Folder containing .dat files with empirical data.
  - `ITOT1_t.dat`: Empirical data for the infected population (I).
  - `ITOT2_t.dat`: Empirical data for the reinfected population (I' or i).
  - `ITOT_t.dat`: Empirical data for the infected + reinfected population (I+ i).
  - `NTOT_t.dat`: Empirical data for the total population (N).
  - `RTOT_t.dat`: Empirical data for the recovered population (R).
  - `STOT1_t.dat`: Empirical data for the susceptible population (S).
  - `STOT2_t.dat`: Empirical data for the re-infected population (S' or s).
  - `STOT_t.dat`: Empirical data for the susceptible and resusceptible population (S + s).
- `RSV_Simulation_Project.ipynb`: Jupyter notebook containing all scripts for easy execution and visualization.
- `README.md`: This file.



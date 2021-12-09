---
title: "A Tutorial on Time-Dependent Cohort State-Transition Models in R using a Cost-Effectiveness Analysis Example"
collection: publications
permalink: /software/2021-08-30-time-dependent-cohort
excerpt: ''
date: 2021-08-30
venue: 'Zenodo'
softwareurl: 'https://zenodo.org/badge/latestdoi/357371663'
citation: 'Alarid-Escudero F, Krijkamp EM, Enns EA, Yang A, Hunink MGM, Pechlivanoglou P, Jalal H (2021). R Code for A Tutorial on Time-Dependent Cohort State-Transition Models in R using a Cost-Effectiveness Analysis Example (Version v0.1.0). Zenodo. 10.5281/zenodo.5338819.'
---

This GitHub repository provides the code of the tutorial on how to implement time-dependent cohort state-transition models (cSTMs) in R using a cost-effectiveness analysis (CEA) example, explained in the following manuscript:

- Alarid-Escudero F, Krijkamp EM, Enns EA, Yang A, Hunink MGM, Pechlivanoglou P, Jalal H. A Tutorial on Time-Dependent Cohort State-Transition Models in R using a Cost-Effectiveness Analysis Example. arXiv:2108.13552v1. 2021:1-37.

The release that accompanies the published article has been archived in [zenodo](https://zenodo.org/badge/latestdoi/357371663).

The `R` folder includes two different scripts corresponding to functions used to synthesize cSTMs outputs and conduct several sensitivity analyses:

- `Funtions.R`: Functions to generate epidemiological measures from time-dependent cSTMs. 

- `Functions_cSTM_time_dep_simulation.R`: These functions wrap the simulation-time dependent cSTM, compute CEA measures, and generate probabilistic sensitivity analysis (PSA) input datasets.

- `Functions_cSTM_time_dep_state_residence.R`: These functions wrap the state-residence time dependent cSTM, compute CEA measures, and generate probabilistic sensitivity analysis (PSA) input datasets.


[GitHub repository](https://github.com/DARTH-git/cohort-modeling-tutorial-timedep) and the accompanying manuscript can be downloaded [here](https://arxiv.org/abs/2108.13552). 

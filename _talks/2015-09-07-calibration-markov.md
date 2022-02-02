---
title: "Calibration of piecewise Markov models using a Bayesian change-point analysis through an iterative convex optimization algorithm"
collection: talks
type: "Conference proceedings talk"
permalink: /talks/2015-09-07-calibration-markov
venue: "ISPOR 5th Latin America Conference"
date: 2015-09-07
location: "Santiago, Chile"
---

## Abstract
### Purpose
Relative survival, as reported by the Surveillance, Epidemiology, and End Results (SEER) Program, represents cancer survival in the absence of other causes of death.  Often, cancer Markov models have a distant metastasis state, a state not directly observed in SEER, from which cancer deaths are presumed to occur. The aim of this research is to use a novel approach to calibrate the transition probabilities to and from an unobserved state of a Markov model to fit a relative survival curve.

### Methods
We modeled relative survival through a three-piecewise Markov model (i.e., with a specific Markov chain within each specified pieces) for stage 3 colorectal cancer patients. For each piece we used a constant transition matrix with three states: 1) recurrence free, 2) metastatic recurrence and 3) dead from cancer. We estimated the optimal cutoff time points using a Bayesian Markov chain Monte Carlo (MCMC) change-point model. This technique allowed us to estimate the time points at which the slope of the relative survival changes. We calibrated the transition probabilities using a two-step iterative convex optimization algorithm previously published. The dynamics of the disease can be defined as xt+1= xtM, where xt+1 is the state vector that results from the transformation given by the monthly transition matrix M. The matrix M is a piecewise block-diagonal matrix that includes in each piece a block-diagonal matrix for each Markov chain.

### Results
We applied our method to calibrate a Markov model to fit a relative survival curve for stage 3 colorectal cancer patients younger than 75 years old. We compared our piecewise calibration method to a single-piece approach (i.e., a Markov chain). While the single-piece converged faster, the piecewise method improved the goodness of fit by 60%. The mean of the change points estimated from the Bayesian change-point model was at months 3 and 24 (see figure). The observed, and the piecewise and single-piece calibrated relative survival curves are shown in the figure.

### Conclusions
By estimating the change points in the relative survival curve we were able to find the optimal transition probabilities for a piecewise Markov model that allowed us to impose a particular structure defined by the progression of the disease. We propose a piecewise calibration method that produces more accurate solutions compared to a single-piece approach.
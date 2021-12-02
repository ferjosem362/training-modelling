---
title: "A Gaussian Approximation Approach for Value of Information Analysis"
collection: publications
permalink: /publication/2017-07-22-gaussian-approximation
excerpt: ''
date: 2017-07-22
venue: 'Medical Decision Making'
paperurl: 'https://doi.org/10.1177/0272989X17715627'
citation: 'Jalal H, Alarid-Escudero F. A Gaussian Approximation Approach for Value of Information Analysis. Medical Decision Making, 2018;38(2):174-188.
---

## Abstract
Most decisions are associated with uncertainty. Value of information (VOI) analysis quantifies the opportunity loss associated with choosing a suboptimal intervention based on current imperfect information. VOI can inform the value of collecting additional information, resource allocation, research prioritization, and future research designs. However, in practice, VOI remains underused due to many conceptual and computational challenges associated with its application. Expected value of sample information (EVSI) is rooted in Bayesian statistical decision theory and measures the value of information from a finite sample. The past few years have witnessed a dramatic growth in computationally efficient methods to calculate EVSI, including metamodeling. However, little research has been done to simplify the experimental data collection step inherent to all EVSI computations, especially for correlated model parameters. This article proposes a general Gaussian approximation (GA) of the traditional Bayesian updating approach based on the original work by Raiffa and Schlaifer to compute EVSI. The proposed approach uses a single probabilistic sensitivity analysis (PSA) data set and involves 2 steps: 1) a linear metamodel step to compute the EVSI on the preposterior distributions and 2) a GA step to compute the preposterior distribution of the parameters of interest. The proposed approach is efficient and can be applied for a wide range of data collection designs involving multiple non-Gaussian parameters and unbalanced study designs. Our approach is particularly useful when the parameters of an economic evaluation are correlated or interact.

[Download paper here](https://doi.org/10.1177/0272989X17715627) and the accompanying R package can be downloaded [here](https://github.com/feralaes/VOI-Gaussian-Approximation).

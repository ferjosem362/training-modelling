---
title: "A Tutorial on Time-Dependent Cohort State-Transition Models in R using a Cost-Effectiveness Analysis Example"
collection: publications
permalink: /publication/2022-09-16-time-dependent-cohort
excerpt: 'This tutorial shows how to implement time-dependent cohort state-transition models (cSTMs) to conduct cost-effectiveness analyses (CEA) in R, where transition probabilities and rewards vary by time.'
date: 2022-09-16
venue: 'Medical Decision Making'
paperurl: 'https://doi.org/10.1177/0272989X221121747'
citation: 'Alarid-Escudero F, Krijkamp EM, Enns EA, Yang A, Hunink MGM, Pechlivanoglou P, Jalal H. A Tutorial on Time-Dependent Cohort State-Transition Models in R using a Cost-Effectiveness Analysis Example. Medical Decision Making. 2022;(Online First).'
---

## Abstract
In an introductory tutorial, we illustrated building cohort state-transition models (cSTMs) in R, where the state transition probabilities were constant over time. However, in practice, many cSTMs require transitions, rewards, or both to vary over time (time dependent). This tutorial illustrates adding 2 types of time dependence using a previously published cost-effectiveness analysis of multiple strategies as an example. The first is simulation-time dependence, which allows for the transition probabilities to vary as a function of time as measured since the start of the simulation (e.g., varying probability of death as the cohort ages). The second is state-residence time dependence, allowing for history by tracking the time spent in any particular health state using tunnel states. We use these time-dependent cSTMs to conduct cost-effectiveness and probabilistic sensitivity analyses. We also obtain various epidemiological outcomes of interest from the outputs generated from the cSTM, such as survival probability and disease prevalence, often used for model calibration and validation. We present the mathematical notation first, followed by the R code to execute the calculations. The full R code is provided in a public code repository for broader implementation.

[Download paper here](https://journals.sagepub.com/doi/10.1177/0272989X221121747) and the accompanying R code can be downloaded [here](https://github.com/DARTH-git/cohort-modeling-tutorial-timedep).
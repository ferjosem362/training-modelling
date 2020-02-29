---
title: "A Multidimensional Array Representation of State-transition Model Dynamics"
collection: publications
permalink: /publication/2020-01-28-multidimensional-array
excerpt: 'This paper is about the use of multidimensional arrays to represent and store transition dynamics of simulated cohorts with state-transition models.'
date: 2020-01-28
venue: 'Medical Decision Making'
paperurl: 'https://doi.org/10.1177/0272989X19893973'
citation: 'Krijkamp E, Alarid-Escudero F, Enns EA, Pechlivanoglou P, Hunink MGM, Yang A, Jalal H. (2020). &quot;A Multidimensional Array Representation of State-transition Model Dynamics.&quot; <i>Medical Decision Making</i>. (In press).'
---
Cost-effectiveness analyses often rely on cohort state-transition models (cSTMs). The cohort trace is the primary outcome of cSTMs, which captures the proportion of the cohort in each health state over time (state occupancy). However, the cohort trace is an aggregated measure that does not capture information about the specific transitions among health states (transition dynamics). In practice, these transition dynamics are crucial in many applications, such as incorporating transition rewards or computing various epidemiological outcomes that could be used for model calibration and validation (e.g., disease incidence and lifetime risk). In this article, we propose an alternative approach to compute and store cSTMs outcomes that capture both state occupancy and transition dynamics. This approach produces a multidimensional array from which both the state occupancy and the transition dynamics can be recovered. We highlight the advantages of the multidimensional array over the traditional cohort trace and provide potential applications of the proposed approach with an example coded in R to facilitate the implementation of our method.

[Download paper here](https://doi.org/10.1177/0272989X19893973) and the accompanying R code can be downloaded [here](https://github.com/DARTH-git/state-transition-model-dynamics).
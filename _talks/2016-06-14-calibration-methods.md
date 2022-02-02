---
title: "Comparison of calibration methods for natural history simulation models"
collection: talks
type: "Conference proceedings talk"
permalink: /talks/2016-06-14-calibration-methods
venue: "16th Biennial European Conference of the Society for Medical Decision Making"
date: 2016-06-14
location: "London, UK"
---

[Link to abstract here](https://smdm.confex.com/smdm/16BEC/webprogram/Paper9884.html)

## Abstract
### Purpose
Disease natural history models often contain parameters that are unknown or unobservable for different reasons (e.g., ethical or financial). Calibration is the process of estimating these parameters by matching model outputs to observed clinical or epidemiological data. Our objective is to compare four different calibration methods on how they perform recovering the true parameters.

### Method
Using a known set of parameters, we used a state-transition model with four health states: Healthy, two stages of illness (S1, S2), and Dead to simulate 1,000 individuals over 30 years in a microsimulation fashion. We produced three different sets of targets: survival, disease prevalence and log-ratio between the two stages of illness. We repeated this procedure 100 times to generate multiple sets of calibration targets. We calibrated a cohort version of the model assuming three input parameters were unknown using four different approaches: 1) two goodness-of-fit (GoF) approaches based on absolute differences with equal and unequal weights, 2) a Bayesian sampling-importance-resampling (SIR) approach, and 3) a Pareto frontier approach. We considered scenarios of varying calibration target data availability with observations every 1, 2, 5 and 10 years. We compared the calibration approaches using three metrics: 1) root mean square error (RMSE) between best-fitting input sets and true parameter values, 2) the proportion of simulations in which true parameter values are contained within the bounding ellipse of best-fitting parameters (coverage), and 3) minimum quantile ellipse that contains the true parameter values.

### Results
For the scenario with targets every 5 years (i.e., 18 calibration targets), the Bayesian approach yielded the smallest RMSE, followed by the Pareto frontier. Pareto frontier had the highest coverage, with 94% of the 95% bounding ellipse including the true parameters, followed by the GoF with unequal weights with 82%. Both GoF with equal weights and Pareto frontier had the lowest minimum coverage with 76%. The rest of the results for this scenario are shown in the table. As the number of targets increased all calibration approaches improved.

### Conclusions
Recovering the truth depends on many system and model properties. The choice of calibration targets matter and contrary to what we expected, more targets may not necessarily be better.
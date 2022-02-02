---
title: "Bayesian prediction of prevalence of human papillomavirus in young girls in the US from aggregated data using exponentially damped polynomial models"
collection: talks
type: "Conference proceedings talk"
permalink: /talks/2016-10-24-bayesian-prediction
venue: "38th Annual North American Meeting of the Society for Medical Decision Making"
date: 2016-10-24
location: "Vancouver, Canada"
---

[Link to abstract here](https://smdm.confex.com/smdm/2016bc/webprogram/Paper10498.html)

## Abstract

### Purpose
Recent studies of cervical cancer screening with human papillomavirus (HPV) often do not collect information on infection status in young girls (e.g., <16yo). However, the estimated initial age of onset of sexual activity is typically lower than the age of the populations included in these studies. The aim of this research is to use nonlinear models to predict the prevalence of HPV in young girls for whom data are not typically collected.

### Methods
We modeled the number of women with HPV, yx, at age x as a binomial distributed random variable. The prevalence of HPV infection depends on age. While ample data exist to estimate this prevalence above age 16, there are fewer data below that age. We assume the prevalence, across all ages, follows an exponentially damped polynomial model form. We are able to estimate this function using data on those older than 16 years old (for whom data are available) and use the estimated function to impute the prevalence for those <16 years of age (for whom data are scarce). We estimated the parameters for the exponentially damped polynomial model using Markov chain Monte Carlo (MCMC) methods. We tested different polynomial degrees and age of onset of sexual activity, and selected the model based on deviance information criterion (DIC).

### Results
We estimated the proposed nonlinear model using data from a population-based study of HPV prevalence in the United States reported by age groups prior to mass HPV vaccination. The exponentially damped polynomial model with the lowest DIC is of degree one with an onset of sexual activity at 12 years old. With the estimated model we predicted the HPV prevalence on young girls, which peaked at 38% by the age of 18. The aggregated data and the predicted HPV prevalence by age with its 95% credible interval are shown in the figure.

### Conclusion
By estimating the exponentially damped polynomial model we were able to predict the prevalence of HPV by age, specifically for lower ages where data are not typically collected. By using a Bayesian framework, we were able to incorporate the uncertainty based on the size of the study sample and reflect this uncertainty on the predicted prevalence. 

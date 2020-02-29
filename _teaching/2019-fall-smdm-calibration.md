---
title: "Hands-on Model Calibration in R"
collection: teaching
type: "Shourt course"
permalink: /teaching/2019-fall-smdm-calibration
venue: "41st Annual North American Meeting of SMDM"
date: 2019-10-20
location: "Portland, OR"
---
## [Hands-on Model Calibration in R](https://smdm.confex.com/smdm/2019/meetingapp.cgi/Session/2981) 

### Background
In developing mathematical models of disease processes for medical decision making, there are often a subset of model parameters that cannot be observed for physical, practical, or ethical reasons. For example, cancer progression rates prior to detection cannot, by definition, be directly observed. Calibration is the process by which values of uncertain or unknown parameters are estimated such that model outputs match observed clinical or epidemiological data (“calibration targets”). Generally, calibration involves two main components: 1) a strategy for searching through the space of the unknown parameters; and 2) a goodness-of-fit measure that reflects how well a set of model outputs matches the target data. In this course, we will cover how to implement different approaches to each of these steps in R. We will also provide guidance on the pros and cons of different approaches and the circumstances under which some approaches may be more appropriate than others.

### Course Type
Half day short course

### Course Level
Intermediate

### Format Requirements
This course will include a brief conceptual presentation of model calibration and an extensive hands-on programming exercise in R using code templates. Participants are assumed to be proficient in R and will need to bring their own laptops with the latest versions of R and RStudio installed. Installation instructions will be provided in advance. This course is intended for individuals familiar with mathematical models (e.g., Markov models, infectious disease models, and/or microsimulation) and their application. Some familiarity with the concepts of model calibration is recommended, but not required.

### Overview
Model calibration is the process of estimating values for unknown or uncertain parameters of a mathematical model by matching model outputs to observed data. Commercially-available decision analytic software is generally limited in its model calibration capabilities. R is a programming environment traditionally used for statistical analysis that is being adopted more and more for economic evaluation and decision analytic modeling. R has advantages over commercially available decision analytic software in that it is freely available, highly customizable, facilitates model transparency and reproducibility, and can accommodate a wide range of model calibration approaches. In this course, participants will learn how to calibrate mathematical models in R. We will first cover the fundamental principles of calibration. We will then demonstrate the implementation of the most common calibration approaches, including random search, directed search, and Bayesian methods. Tradeoffs between different calibration methods will be discussed.
### Description & Objectives
In this course, we will cover the steps and decisions involved in calibrating a mathematical model in R. We will begin the course with an overview of when model calibration is necessary and will introduce a general model calibration framework. We will then engage students in an extensive hands-on exercise where they will implement the calibration of a simple mathematical model in R using a simple random search. We will then introduce more advanced calibration approaches, including Latin hypercube sampling, directed search algorithms (e.g., Nelder-Mead), Bayesian calibration, and other iterative calibration approaches (e.g., genetic algorithms). We will discuss the tradeoffs of different calibration approaches and will identify scenarios when one approach may be more appropriate than others.

At the end of the course, participants will be able to:

* Understand the choices that must be made when calibrating a model
* Correctly interpret the results of a model calibration and visualize these results in R
* Implement the calibration of an existing model in R using any of the following approaches:
    * Random search
    * Latin hypercube sampling
    * Directed search with the Nelder-Mead algorithm
    * Bayesian calibration using the Metropolis-Hastings algorithm
    * Genetic algorithms
    * Understand the strengths and weaknesses of different calibration approaches

All R programming templates used in this short course will be provided to participants after the course for future use.

### Description
In developing mathematical models of disease processes for medical decision making, there are often a subset of model parameters that cannot be observed for physical, practical, or ethical reasons. For example, cancer progression rates prior to detection cannot, by definition, be directly observed. Calibration is the process by which values of uncertain or unknown parameters are estimated such that model outputs match observed clinical or epidemiological data (“calibration targets”). Generally, calibration involves two main components: 1) a strategy for searching through the space of the unknown parameters; and 2) a goodness-of-fit measure that reflects how well a set of model outputs matches the target data. In this course, we will cover how to implement different approaches to each of these steps in R. We will also provide guidance on the pros and cons of different approaches and the circumstances under which some approaches may be more appropriate than others.

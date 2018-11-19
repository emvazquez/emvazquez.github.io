---
title: "Research"
permalink: /bdace/
author_profile: true
---

Design and analysis of computer experiments consists in using statistical approaches to problems such as  approximation, uncertainty quantification, optimization... involving computer programs (or simulators) that emulate physical systems (see, e.g., [Santner 2003](https://www.springer.com/fr/book/9780387954202)).

My work relies on the Bayesian sequential decision theory.  In the domain of computer experiments, the Bayesian approach starts with a prior distribution that represents our prior belief about the structure of the computer model. The use of this approach  for computer experiments appeared in the 1980s (see the seminal article by [Sacks et al. (1989)](https://projecteuclid.org/euclid.ss/1177012413)).

Bayesian Optimization
------

How to optimize the performance of a system using numerical simulations? In particular, when simulations are time-consuming, it becomes essential to consider optimization algorithms that use the information provided by the simulations as efficiently as possible. Several approaches may be used. Most of them are based on the construction of an approximation of the output of the simulation (a metamodel). For instance, the idea of the Bayesian approach for optimization is to use a random process as a model of the function to be optimized. Then, the optimization is performed by making evaluations of the function in sequence, each evaluation being chosen in order to minimize a criterion that quantifies the expected loss, under the random process model, incurred by taking the best evaluation result collected so far instead of the true unknown optimum. Both theoretical and practical aspects are considered in my work. 

Estimation of a probability of failure
------

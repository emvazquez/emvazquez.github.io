---
title: "Research"
permalink: /bdace/
author_profile: true
---

_Design and analysis of computer experiments_ is about using statistical approaches to problems such as  approximation, uncertainty quantification, optimization... involving computer programs that emulate physical systems (see, e.g., [Santner 2003](https://www.springer.com/fr/book/9780387954202)).

My work relies on the Bayesian sequential decision theory.  In the domain of computer experiments, the Bayesian approach starts with a prior distribution that represents our prior belief about the structure of the computer model (see, e.g., the seminal article by [Sacks et al. 1989](https://projecteuclid.org/euclid.ss/1177012413)). Mostly often, prior distribution for modeling computer models are derived from Gaussian processes (GP). The use of GP models have become a well-established framework beyond the domain of computer experiments (see, e.g. [C.E. Rassmussen & C.K.I Williams 2006, Gaussian processes for ML](http://www.gaussianprocess.org/gpml/)).

Stepwise Uncertainty Reduction (SUR)
------

By 2006, I suggested using a sequential approach for the estimation of the volume of excursion of a function above a threshold. This problem find a direct application to the estimation of a probability of failure of a system. This work was the first instance of a SUR algorithm, which was improved and published during the period 2009--2013. See for instance [Bect et al. 2011, Sequential design of computer experiments for the estimation of a probability of failure](https://link.springer.com/article/10.1007/s11222-011-9241-4).

The consistency of several SUR strategies has been proved in [Bect et al 2018](https://arxiv.org/abs/1608.01118).

Bayesian Optimization
------

How to optimize the performance of a system using numerical simulations? In particular, when simulations are time-consuming, it becomes essential to consider optimization algorithms that use the information provided by the simulations as efficiently as possible. Several approaches may be used. Most of them are based on the construction of an approximation of the output of the simulation (a metamodel). For instance, the idea of the Bayesian approach for optimization is to use a random process as a model of the function to be optimized. Then, the optimization is performed by making evaluations of the function in sequence, each evaluation being chosen in order to minimize a criterion that quantifies the expected loss, under the random process model, incurred by taking the best evaluation result collected so far instead of the true unknown optimum. Both theoretical and practical aspects are considered in my work, e.g.:
 * [An informational approach to the global optimization of expensive-to-evaluate functions](https://link.springer.com/article/10.1007/s10898-008-9354-2) in 2008
 * [Convergence properties of the expected improvement algorithm with fixed mean and covariance functions](https://www.sciencedirect.com/science/article/pii/S0378375810001850) in 2010
 * [Robust Gaussian Process-Based Global Optimization Using a Fully Bayesian Expected Improvement Criterion](https://link.springer.com/chapter/10.1007%2F978-3-642-25566-3_13) in 2011
 * [A Bayesian approach to constrained single- and multi-objective optimization](https://link.springer.com/article/10.1007/s10898-016-0427-3) in 2017
 * ...



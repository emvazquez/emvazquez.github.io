---
title: "Research"
permalink: /bdace/
author_profile: true
---

_Design and analysis of computer experiments_ is about using statistical approaches to problems such as  approximation, uncertainty quantification, optimization... involving computer programs that emulate physical systems (see, e.g., [Santner 2003](https://www.springer.com/fr/book/9780387954202)).

My work relies on the Bayesian sequential decision theory.  In the domain of computer experiments, the Bayesian approach starts with a prior distribution that represents our prior belief about the structure of the computer model (see, e.g., the seminal article by [Sacks et al. 1989](https://projecteuclid.org/euclid.ss/1177012413)). Mostly often, prior distribution for modeling computer models are derived from Gaussian processes (GP). The use of GP models have become a well-established framework beyond the domain of computer experiments (see, e.g. [C.E. Rassmussen & C.K.I Williams 2006, Gaussian processes for ML](http://www.gaussianprocess.org/gpml/)).

Stepwise Uncertainty Reduction (SUR)
------

My work about SUR strategies began by 2006, when I undertook the supervision of Miguel
Piera-Martinez during his PhD thesis. We focused our work on the problem of modeling the occurrence of extreme values in the output of a computer program---these extreme values may correspond to
abnormal or dangerous operating conditions.  A simple Monte Carlo analysis of extreme values requires many simulations of the system, which are often very expensive. It is thus desirable to analyze extreme events with as few system simulations as possible.

Our first idea was to use the statistical theory of extreme values to model the tail distribution of the output of a computer model. We could obtain satisfactory results by applying [Extreme Value Theory (EVT)](https://en.wikipedia.org/wiki/Extreme_value_theory) to various problems in the domain of electronic design and electromagnetic compatibility engineering. We were also interested in using EVT and machine learning techniques to estimate multivariate quantiles. Later on, I suggested using a sequential approach for the estimation of a probability of failure. This was the first instance of a SUR algorithm. This work was improved and published during the period 2009--2013. See for instance [Bect et al. 2011, Sequential design of computer experiments for the estimation of a probability of failure](https://link.springer.com/article/10.1007/s11222-011-9241-4).

The consistency of several SUR strategies has been proved in [Bect et al 2018](https://arxiv.org/abs/1608.01118).

Bayesian Optimization
------

How to optimize the performance of a system using numerical simulations? In particular, when simulations are time-consuming, it becomes essential to consider optimization algorithms that use the information provided by the simulations as efficiently as possible. Several approaches may be used. Most of them are based on the construction of an approximation of the output of the simulation (a metamodel). For instance, the idea of the Bayesian approach for optimization is to use a random process as a model of the function to be optimized. Then, the optimization is performed by making evaluations of the function in sequence, each evaluation being chosen in order to minimize a criterion that quantifies the expected loss, under the random process model, incurred by taking the best evaluation result collected so far instead of the true unknown optimum. Both theoretical and practical aspects are considered in my work:
 * [An informational approach to the global optimization of expensive-to-evaluate functions](https://link.springer.com/article/10.1007/s10898-008-9354-2)
 * [Convergence properties of the expected improvement algorithm with fixed mean and covariance functions](https://www.sciencedirect.com/science/article/pii/S0378375810001850)
 * [Robust Gaussian Process-Based Global Optimization Using a Fully Bayesian Expected Improvement Criterion](https://link.springer.com/chapter/10.1007%2F978-3-642-25566-3_13)
 * [A Bayesian approach to constrained single- and multi-objective optimization](https://link.springer.com/article/10.1007/s10898-016-0427-3)



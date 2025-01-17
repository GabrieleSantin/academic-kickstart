---

title: "Kernel Methods for Surrogate Modeling"
author_list: G. Santin, B. Haasdonk
abstract: "This chapter deals with kernel methods as a special class of techniques for surrogate modeling. Kernel methods have proven to be efficient in machine learning, pattern recognition and signal analysis due to their flexibility, excellent experimental performance and elegant functional analytic background. These data-based techniques provide so called kernel expansions, i.e., linear combinations of kernel functions which are generated from given input-output point samples that may be arbitrarily scattered. In particular, these techniques are meshless, do not require or depend on a grid, hence are less prone to the curse of dimensionality, even for high-dimensional problems. 
In contrast to projection-based model reduction, we do not necessarily assume a high-dimensional model, but a general function that models input-output behavior within some simulation context. This could be some micro-model in a multiscale-simulation, some submodel in a coupled system, some initialization function for solvers, coefficient function in PDEs, etc. 
First, kernel surrogates can be useful if the input-output function is expensive to evaluate, e.g. is a result of a finite element simulation. Here, acceleration can be obtained by sparse kernel expansions. Second, if a function is available only via measurements or a few function evaluation samples, kernel approximation techniques can provide function surrogates that allow global evaluation. 
We present some important kernel approximation techniques, which are kernel interpolation, greedy kernel approximation and support vector regression. Pseudo-code is provided for ease  of reproducibility. In order to illustrate the main features, commonalities and differences, we compare these techniques on a real-world application. The experiments clearly indicate the enormous acceleration potential."
#tags: [tag1, tag2]
arxiv: "https://arxiv.org/abs/1907.10556"
year: "2019"
date: 2019-01-01
---



---

title: "Greedy kernel methods for accelerating implicit integrators for parametric ODEs"
author_list: T. Br&uuml;nnette, G. Santin, and B. Haasdonk
abstract: "We present a novel acceleration method for the solution of parametric ODEs by single-step implicit solvers by means of greedy kernel-based surrogate models. In an offline phase, a set of trajectories is precomputed with a high-accuracy ODE solver for a selected set of parameter samples, and used to train a kernel model which predicts the next point in the trajectory as a function of the last one. This model is cheap to evaluate, and it is used in an online phase for new parameter samples to provide a good initialization point for the nonlinear solver of the implicit integrator. The accuracy of the surrogate reflects into a reduction of the number of iterations until convergence of the solver, thus providing an overall speedup of the full simulation. Interestingly, in addition to providing an acceleration, the accuracy of the solution is maintained, since the ODE solver is still used to guarantee the required precision. Although the method can be applied to a large variety of solvers and different ODEs, we will present in details its use with the Implicit Euler method for the solution of the Burgers equation, which results to be a meaningful test case to demonstrate the method's features."
doi: "https://doi.org/10.1007/978-3-319-96415-7_84"
arxiv: "https://arxiv.org/abs/1802.08106"
abbrv_journal: "Numerical Mathematics and Advanced Applications ENUMATH 2017,  F.A. Radu, K. Kumar, I. Berre, J.M. Nordbotten, I.S. Pop, Eds"
pages: "889-896"
year: "2019"
date: 2019-01-01
---



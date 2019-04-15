# thirdyearproj
This repository contains a set of notebooks created for the third year project for my BSc in Mathematics at the University of York. The project is titled "Statistical Inference for Ordinary Differential Equations". So far, the aim of this project is to infer the distribution of parameters belonging to differential equations, after observing experimental data from the system. I will be taking a Bayesian approach to my project and intend to make use of Markov Chain Monte Carlo techniques. This repository hosts several notebooks that show how the results  displayed in my dissertation were produced, these are placed under the Dissertation  title. Other notebooks, that aided my development and understand can be found in the Misc section.

#### Note:
Some of these notebooks feature animated plots to display how inference changes with each observation. Such plots cannot be displayed on GitHub and must be ran locally. To do so, FFmpeg must be installed and \FFmpeg\bin added to PATH.

##  Dissertation
- DRAFT of disseration [here](https://github.com/thomasarmstrong98/thirdyearproj/blob/master/thomas_armstrong.pdf)

- Grid Approximation (Logistic Eqn) [here](https://github.com/thomasarmstrong98/thirdyearproj/blob/master/two_param_logitic_grid_approx.ipynb)
- Metropolis-Hastings (Logistic Eqn) [here](https://github.com/thomasarmstrong98/thirdyearproj/blob/master/two_param_mcmc_logisitc_eqn.ipynb)
- Metropolis-Hastings (Competition Model) [here](https://github.com/thomasarmstrong98/thirdyearproj/blob/master/complex_lotka_volterra.ipynb)
- Evaluation of MCMC techniques. [here](https://github.com/thomasarmstrong98/thirdyearproj/blob/master/dissertation_eval_graphs.ipynb) 

## Misc
### Structure of Notebooks:

#### Grid Estimation 
- Coin Toss Example, [here](https://github.com/thomasarmstrong98/thirdyearproj/blob/master/bayesian_coin_toss_bias.ipynb)
- One Parameter Logistic Equation, [here](https://github.com/thomasarmstrong98/thirdyearproj/blob/master/bayesian_logistic_eqn_grid.ipynb)
- Two Parameter Normal Distribution, [here](https://github.com/thomasarmstrong98/thirdyearproj/blob/master/grid_approx_two_param_normal.ipynb)
- Two Parameter Logistic Equation, [here](https://github.com/thomasarmstrong98/thirdyearproj/blob/master/two_param_logitic_grid_approx.ipynb)
  
#### MCMC
- Two Parameter Logistic Equation (Unfinished) [here](https://github.com/thomasarmstrong98/thirdyearproj/blob/master/logistic_two_param_mcmc.ipynb)
- Altered Lotka Volterra with Bi-modal Posterior [here](https://github.com/thomasarmstrong98/thirdyearproj/blob/master/altered_lotka_volterra_mcmc.ipynb)

#### Extra (Some work on using ODE solvers for dynamical systems)
- Lotka Volterra Predator Prey [here](https://github.com/thomasarmstrong98/thirdyearproj/blob/master/ode_solver_exploration.ipynb)

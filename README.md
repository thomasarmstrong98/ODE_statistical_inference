# thirdyearproj
This repository contains a set of notebooks created for the third year project of my BSc in Mathematics at the University of York. The project is titled "Bayesian Statistical Inference for Ordinary Differential Equations". The aim of this project is to infer the posterior distribution of parameters belonging to systems differential equations, after observing experimental data from the system. I will evidently be taking a Bayesian approach to my project and intend to make use of Markov Chain Monte Carlo techniques. This repository hosts several notebooks that show how the results  displayed in my dissertation were produced, these are placed under the Dissertation  title. Other notebooks, that aided my development and understanding can be found in the Misc section.

#### Supervision:
This project was supervised by Gustav Delius. I am extremely thankful for the many discussions that I have shared with Gustav, both for his insight into this specific project but also for the words of support regarding my future career as a mathematician.
#### Note:
- The deadline for my dissertation was the 7th of May, as a result all the notebooks in the Dissertation will remain un-altered to preserve my results. For updated or improved notebooks, see the Updated subsection.

- Some of these notebooks feature animated plots to display how inference changes with each observation. Such plots cannot be displayed on GitHub and must be ran locally. To do so, FFmpeg must be installed and \FFmpeg\bin added to PATH.

- If you believe there to be an error in my code or wish to discuss further about the topics explored in this repository, feel free to reach out to me at thomasarmstrong98\~at~gmail\~dot~com.
##  Dissertation
- DRAFT of disseration [here](https://github.com/thomasarmstrong98/thirdyearproj/blob/master/thomas_armstrong.pdf)

- Grid Approximation (Logistic Eqn) [here](https://github.com/thomasarmstrong98/thirdyearproj/blob/master/two_param_logitic_grid_approx.ipynb)
- Metropolis-Hastings (Logistic Eqn) [here](https://github.com/thomasarmstrong98/thirdyearproj/blob/master/two_param_mcmc_logisitc_eqn.ipynb)
- Metropolis-Hastings (Competition Model) [here](https://github.com/thomasarmstrong98/thirdyearproj/blob/master/complex_lotka_volterra.ipynb)
- Evaluation of MCMC techniques. [here](https://github.com/thomasarmstrong98/thirdyearproj/blob/master/problems_with_mh_mcmc.ipynb) 

### Updated
- empty

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

# GARCH_ZV_MCMC
Implementation of Monte Carlo methods via Markov chains with control variates to evaluate GARCH model parameters.

In MCMC_GARCH.ipynb, there is an implementation of a random walk Metropolis sampler that aims to estimate the posterior distribution of a GARCH model with real data.

In ZVMCMC_GARCH.ipynb, we include the use of control variates (specifically, a first-order polynomial) to implement the zero variance Markov chain Monte Carlo method for estimating the posterior distribution of a GARCH model. To observe the improvement in estimation, you can take a look at the boxplot located at the end of the file.

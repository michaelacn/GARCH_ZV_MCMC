# GARCH_ZV_MCMC
Implementation of Monte Carlo methods via Markov chains with control variates to evaluate GARCH model parameters.

# Notes

In MCMC_GARCH.ipynb, there is an implementation of a random walk Metropolis sampler that aims to estimate the posterior distribution of a GARCH model with simulated and real data.

In ZVMCMC_GARCH.ipynb, we include the use of control variates (specifically, a first-order polynomial) to implement the zero variance Markov chain Monte Carlo method for estimating the posterior distribution of a GARCH model. To observe the improvement in estimation, you can take a look at the boxplot located at the end of the file.

# Bibliography 
Antonietta Mira, Reza Solgi and Daniele Imparato (2011). Zero Variance Markov Chain Monte Carlo for Bayesian Estimators. Available at : https://www.eco.uninsubria.it/RePEc/pdf/QF2011_09.pdf

# Bayesian inference

* It natively incorporates the idea of confidence, it performs well with sparse data, and the model and results are highly interpretable and easy to understand.
* Suitable for prediction of relatively small or scattered dataset
* It can be use anywhere you need a clear understanding of your uncertainty.

## Notes:

* Likelihood: How probable is the evidence given that our hypothesis is true? 

* Prior: How probable was our hypothesis before observing the evidence?

* Posterior: How probable is our hypothesis given the observed evidence?

* Marginal: How probable is the new evidence under all possible?
   
* The MCMC (Markov Chain Monte Carlo) method is an algorithm used to sample from a probability distribution. MCMC samples from the prior for each parameter, trying to maximize the probabilty of the parameter given the data.
   
* A hands-on application-based book , available free online [Bayesian Methods for Hackers](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers).

* The library for probabilistic programming and Bayesian Inference in Python is [PyMC3](https://github.com/pymc-devs/pymc).

* [Bambi](https://github.com/bambinos/bambi) is a high-level Bayesian model-building interface written in Python. It's built on top of the PyMC3 probabilistic programming framework, and is designed to make it extremely easy to fit mixed-effects models common in social sciences settings using a Bayesian approach.

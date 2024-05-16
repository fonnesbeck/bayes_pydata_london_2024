# Probabilistic Programming and Bayesian Computing with PyMC

Bayesian statistical methods provide powerful tools for solving various data science problems. The Bayesian approach yields easy-to-interpret results and automatically accounts for uncertainty in our estimates or predictions. Although computational challenges have historically been an obstacle, especially for new users, there are now mature probabilistic programming tools that are both efficient and easy to learn. We will use the latest release of PyMC (version 5) for this tutorial, but the concepts and techniques taught can be applied to any probabilistic programming framework.

This tutorial targets practicing and aspiring data scientists and analysts who seek to incorporate Bayesian statistics and probabilistic programming into their work. It will provide new users with an overview of Bayesian statistical methods and their applicability in various situations. Learners will also gain practical experience in applying these methods using PyMC, including the specification, fitting, and validation of models using a real-world dataset.

The tutorial's goal is to enable new users to use Bayesian methods effectively. We will keep the theory light and focus on the practical implementation of models, while still providing some statistical background for context and clarity. Since PyMC is a high-level statistical package, it's easy to overlook important details of the underlying algorithms. So we'll start the tutorial by solving a simple model using only NumPy and SciPy functions before moving on to PyMC. As a culmination of the tutorial, I will introduce "The Bayesian Workflow", reiterating the crucial steps in the process and offering helpful tips and tricks to help make Bayesian modeling fool-proof.

This is an introductory tutorial, so no prior experience with PyMC or Bayesian statistics is required. However, for maximum benefit, learners should be somewhat familiar with basic statistical modeling, such as regression and estimation. They should also be comfortable with using the core components of the scientific Python stack, including NumPy, pandas, and Jupyter.

This tutorial will be presented using Jupyter notebooks, enabling participants to run examples and exercises on their own computers. Two weeks prior to PyData, I will set up a GitHub repository with instructions for setting up the Python environment to run the tutorial locally.

### Syllabus

- Introduction to Probabilistic Programming (10 min)
    - What is Bayesian statistics?
    - What is a probabilistic model?
    - Doing Bayes by hand
- A PyMC Primer (20 min)
    - Priors and likelihoods: how to choose
    - Deterministic quantities
    - Converting math to code
- Estimating models with Markov chain Monte Carlo (15 min)
    - How can we estimate a model with sampling?
    - The Hamiltonian Monte Carlo algorithm
    - MCMC in PyMC
    - What to do when things go wrong!
- Model checking (15 min)
    - Summarizing your model with plots and tables
    - Did our inference algorithm work as expected?
    - Is our model generating reasonable and believable results?
- The Bayesian workflow (30 min)
    - A complete working example, from data import through to interpreting the results
    - Using `do` and `observe`
    - out-of-sample prediction
    - Bayesian best practices

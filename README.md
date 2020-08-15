# The Power of Bayesian Inference estimated using PyMC3 
## If you've steered clear of Bayesian regression because of its complexity, this article looks at how to apply simple MCMC Bayesian Inference to linear data with outliers in Python, using linear regression and Gaussian random walk priors, testing assumptions on observation errors from Normal vs Student-T prior distributions and comparing against ordinary least squares.

![Bayesian Inference](http://www.appliedmachinelearning.ai/assets/images/randomwalk_regression.jpg "Bayesian Inference with PyMC3")

## References
1. T. Wiecki, [GLM: Robust Linear Regression](https://docs.pymc.io/notebooks/GLM-robust.html) (2018), PyMC3
2. J. Salvatier1, T. Wiecki, C. Fonnesbeck, [Probabilistic programming in Python using PyMC3](https://pdfs.semanticscholar.org/8085/b60ce1771647f11ccc4728397275b502f359.pdf) (2016), PeerJ Computer Science
3. J. Salvatier1, C. Fonnesbeck, T. Wiecki, [GLM: Robust Regression with Outlier Detection](https://pymc3-testing.readthedocs.io/en/rtd-docs/notebooks/GLM-robust-with-outlier-detection.html) (2016), PyMC3
4. M. Waskom, [seaborn.regplot](https://seaborn.pydata.org/generated/seaborn.regplot.html) (2012-2020), seaborn.pydata
5. J. Jones, M. Mastanduno, T. Larsen, [Machine Learning Versus Statistics: When to use each - healtcare.ai](https://healthcare.ai/machine-learning-versus-statistics-use/ (), healthcare.ai
6. Darrin, [Linear Regression vs Bayesian Regression](https://educationalresearchtechniques.com/2017/10/18/linear-regression-vs-bayesian-regression/) (2017), Educational Research Techniques
7. PyMC3 Development team, [Continuous Distributions](https://docs.pymc.io/api/distributions/continuous.html#pymc3.distributions.continuous.StudentT) (2018), PyMC3 API
8. A. Gelman, [Best practice for Student-T prior](https://statmodeling.stat.columbia.edu/2015/05/17/) (2015), Statistical Modeling, Causal Inference
9. [Bayesian Credible Interval](https://en.wikipedia.org/wiki/Credible_interval) (2020), Wikipedia
10. PyMC3 Development team, [Inference Sampling](https://docs.pymc.io/api/inference.html) (2018), PyMC3 API
11. P. Orbanz, Y. W. Teh, [Bayesian Nonparametric Models](https://www.stats.ox.ac.uk/~teh/research/npbayes/OrbTeh2010a.pdf) (2010), University of Oxford, Department of Statistics
12. T. Iordanova, [An Introduction to Stationary and Non-Stationary Processes](https://www.investopedia.com/articles/trading/07/stationary.asp) (2020), Investopedia
13. A. Gelman, [Prior Choice Recommendations](https://github.com/stan-dev/stan/wiki/Prior-Choice-Recommendations) (2020), stan-dev/stan
14. Hiro, [Bayesian Regression using PyMC3](https://h1ros.github.io/posts/bayesian-regression-using-pymc3/) (2019)
15. Paul, [PYMC3 Bayesian Prediction Cones](https://stackoverflow.com/questions/45828517/pymc3-bayesian-prediction-cones) (2017) stack overflow

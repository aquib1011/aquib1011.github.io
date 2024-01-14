---
title: "Python Package: General-distribution"
excerpt: "This package provides the probability distribution classes.<br/><img src='/images/Pack.jpg'>"
collection: portfolio
---
[Code](https://github.com/aquib1011/general-distribution)
[Documentation](https://pypi.org/project/general-distribution/)

<!-- python code -->
```python
from general_distribution import Gaussian
gaussian_one = Gaussian(25, 2)
gaussian_two = Gaussian(30, 3)
gaussian_sum = gaussian_one + gaussian_two
print(gaussian_sum.mean)
print(gaussian_sum.stdev)
```
## Gaussian 
Gaussian distribution class for calculating and visualizing a Gaussian distribution.
In probability theory, a normal (or Gaussian or Gauss or Laplace–Gauss) distribution is a type of continuous probability distribution for a real-valued random variable.Gaussian distributions have some unique properties that are valuable in analytic studies. For instance, any linear combination of a fixed collection of normal deviates is a normal deviate. Many results and methods (such as propagation of uncertainty and least squares parameter fitting) can be derived analytically in explicit form when the relevant variables are normally distributed.

## Binomial 
 Binomial distribution class for calculating and visualizing a Binomial distribution. In probability theory and statistics, the binomial distribution with parameters n and p is the discrete probability distribution of the number of successes in a sequence of n independent experiments, each asking a yes–no question, and each with its own boolean-valued outcome: success/yes/true/one (with probability p) or failure/no/false/zero (with probability q = 1 − p). A single success/failure experiment is also called a Bernoulli trial or Bernoulli experiment and a sequence of outcomes is called a Bernoulli process; for a single trial, i.e., n = 1, the binomial distribution is a Bernoulli distribution. The binomial distribution is the basis for the popular binomial test of statistical significance.
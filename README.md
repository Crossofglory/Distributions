# Probability Distributions
This repository contains Python scripts that implement two common probability distributions: the Gaussian distribution and the binomial distribution.

Files
gaussian_distribution.py: This file contains a Python class that represents a Gaussian distribution. It provides methods for calculating a Gaussian distribution's mean, standard deviation, and probability density function (PDF). It also includes histogram plotting functions for the distribution.

binomial_distribution.py: This file contains a Python class that represents a binomial distribution. It provides methods for calculating a binomial distribution's mean, standard deviation, and probability density function (PDF). It also includes histogram plotting functions for the distribution.

# Usage
# To use the Gaussian distribution module, import the GaussianDistribution class from #gaussian_distribution.py:
from gaussian_distribution import GaussianDistribution

#Create a Gaussian distribution with mean 0 and standard deviation 1
gaussian = GaussianDistribution(0, 1)

#Calculate the mean of the distribution
mean = gaussian.mean()

#Calculate the standard deviation of the distribution
std_dev = gaussian.standard_deviation()

#Calculate the probability density function (PDF) at a specific value
pdf_value = gaussian.pdf(2.5)

# To use the binomial distribution module, import the BinomialDistribution class from binomial_distribution.py:

from binomial_distribution import BinomialDistribution

#Create a binomial distribution with 10 trials and a success probability of 0.5
binomial = BinomialDistribution(10, 0.5)

#Calculate the mean of the distribution
mean = binomial.mean()

#Calculate the standard deviation of the distribution
std_dev = binomial.standard_deviation()

#Calculate the probability density function (PDF) at a specific value
pdf_value = binomial.pdf(3)

# Dependencies
The scripts require the following dependencies:

Python 3.x
NumPy (for mathematical calculations)




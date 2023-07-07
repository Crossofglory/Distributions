# Probability Distributions
This repository contains Python scripts that implement two common probability distributions: the Gaussian distribution and the binomial distribution.

Files
gaussian_distribution.py: This file contains a Python class that represents a Gaussian distribution. It provides methods for calculating a Gaussian distribution's mean, standard deviation, and probability density function (PDF). It also includes histogram plotting functions for the distribution.

binomial_distribution.py: This file contains a Python class that represents a binomial distribution. It provides methods for calculating a binomial distribution's mean, standard deviation, and probability density function (PDF). It also includes histogram plotting functions for the distribution.

# Usage
## To use the Gaussian distribution module, import the Gaussian class from #gaussian_distribution.py:
from gaussian_distribution import Gaussian

gaussian = GaussianDistribution(0, 1)

mean = gaussian.mean()

std_dev = gaussian.standard_deviation()

pdf_value = gaussian.pdf(2.5)

gaussian.plot_histogram()

gaussian.plot_histogram_pdf()

## To use the binomial distribution module, import the Binomial class from binomial_distribution.py:

from binomial_distribution import Binomial

binomial = BinomialDistribution(0.5, 20)

mean = binomial.mean()

std_dev = binomial.standard_deviation()

pdf_value = binomial.pdf(3)

binomial.plot_histogram()

binomial.plot_histogram_pdf()

# Dependencies
The scripts require the following dependencies:

Python 3.x

NumPy (for mathematical calculations)




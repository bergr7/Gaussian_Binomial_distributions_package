# gaubi_dists package

## Summary of the package

This is a python package that allows the user to calculate statistics (mean and
stdev) and plot pdf of Gaussian and Binomial distributions.

Addition of two different distributions is also included. However, note in the
case of binomial distributions these need to have the same probability.

## Files included in the package

__init__.py - Initializes the classes in the package

Generaldistribution.py - Generic distribution class for calculating and
visualizing a probability distribution (Parent class)

Gaussiandistribution.py - Gaussian distribution class for calculating and
visualizing a Gaussian distribution. (This class inherits from
Generaldistribution.py)

Binomialdistribution.py - Binomial distribution class for calculating and
visualizing a Binomial distribution. (This class inherits from
Generaldistribution.py)

setup.cfg - Reads README.md file.

README.md

## License

MIT license

## Acknowledgements

Udacity Data Science Nanodegree program (Andrew Paster)

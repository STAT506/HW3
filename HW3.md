HW 3
================
Name here

### Q1. Based on GH CH.2 Ex 3 (8 points)

Demonstration of the Central Limit Theorem: let
\(x = x_1 + ... + x_20,\) the sum of 20 independent Uniform(0,1) random
variables. In R, create 1000 simulations of \(x\) and plot their
histogram. On the histogram, overlay a graph of the normal density
function. Comment on any differences between the histogram and the
curve.

*Then repeat the exercise for 10, 50, and 100 independent Uniform random
variables*

### Q2. Based on GH CH.2 Ex 4 (6 points)

Distribution of averages and differences: the heights of men in the
United States are approximately normally distributed with mean 69.1
inches and standard deviation 2.9 inches. The heights of women are
approximately normally distributed with mean 63.7 inches and standard
deviation of 2.7 inches. Let x be the average height of 100 randomly
sampled men, and y be the average height of 100 randomly sampled women.
In R, create 1000 simulations of \(x-y\) and plot their histogram. Using
simulations, compute the mean and standard deviation of the distribution
of \(x-y\). Then compare the simulated results for \(x-y\) to their
exact (analytical) values. Note: if \(z_1 \sim N(\mu_1, \sigma^2_1)\)
and \(z_2 \sim N(\mu_2, \sigma^2_2)\) are independent normal random
variables, then
\(z_1 - z_2 \sim N(\mu_1 - \mu_2, \sigma^2_1 + \sigma^2_2)\)

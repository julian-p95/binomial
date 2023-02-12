# binomial

This code performs a simulation of a binomial distribution to model the number of stickers in 25 notebooks, each with 50 pages, that have a housing advertisement. The goal is to determine the probability of having at least 2 stickers in a notebook.

Data
The data used in this simulation is the number of housing advertisements found in a random sample of 25 notebooks, each with 50 pages. The probability of finding a housing advertisement in one page is calculated as the number of housing advertisements found in the sample (40529) divided by the total number of pages in the sample (150000).

Binomial Distribution
A binomial distribution is used to model the number of successes in a fixed number of independent Bernoulli trials, where the success probability remains constant. In this simulation, the number of successes is the number of stickers found in a notebook, and the number of Bernoulli trials is 50.

Function
A function binom is defined to simulate the binomial distribution. The function takes two arguments, the number of Bernoulli trials (n) and the success probability (p). The function returns the number of successes in the n trials.

Simulation
A for loop is used to simulate the number of stickers in 25 notebooks. The binom function is used to simulate the binomial distribution for each notebook, and the results are stored in the carnets_25 list. Another function, comptage_carnets, is defined to count the number of notebooks with at least 2 stickers.

Results
The results of the simulation are displayed as a bar graph. The x-axis represents the number of stickers found in a notebook, and the y-axis represents the probability of finding that number of stickers. The results of the simulation are compared to the theoretical probabilities calculated using the binomial distribution.

Conclusion
The results of the simulation are in agreement with the theoretical probabilities calculated using the binomial distribution. The probability of finding at least 2 stickers in a notebook is approximately 0.39.

Module 5 - Probability Basics of Probability

    Write a Python program to simulate the following scenarios: a. Tossing a coin 10,000 times and calculating the experimental probability of heads and tails. b. Rolling two dice and computing the probability of getting a sum of 7. Steps a. Use Python's random module for simulations. b. Implement loops for repeated trials. c. Track outcomes and compute probabilities.

    Write a function to estimate the probability of getting at least one "6" in 10 rolls of a fair die. Steps a. Simulate rolling a die 10 times using a loop. b. Track trials where at least one "6" occurs. c. Calculate the proportion of successful trials. Conditional Probability and Bayes' Theorem

    A bag contains 5 red, 7 green, and 8 blue balls. A ball is drawn randomly, its color noted, and it is put back into the bag. If this process is repeated 1000 times, write a Python program to estimate: a. The probability of drawing a red ball given that the previous ball was blue. b. Verify Bayes' theorem with the simulation results. Steps a. Use random sampling to simulate the process. b. Compute conditional probabilities directly from the data. Random Variables and Discrete Probability

    Generate a sample of size 1000 from a discrete random variable with the following distribution:
        P(X=1) = 0.25
        P(X=2) = 0.35
        P(X=3) = 0.4 Compute the empirical mean, variance, and standard deviation of the sample. Steps a. Use numpy.random.choice() to generate the sample. b. Use numpy methods to calculate mean, variance, and standard deviation. Continuous Random Variables

    Simulate 2000 random samples from an exponential distribution with a mean of 5. Visualize the distribution using: a. A histogram. b. A probability density function (PDF) overlay. Steps a. Use numpy.random.exponential(). b. Use matplotlib to create visualizations. Central Limit Theorem

    Simulate the Central Limit Theorem by following these steps a. Generate 10,000 random numbers from a uniform distribution. b. Draw 1000 samples of size n = 30. c. Calculate and visualize the distribution of sample means. Steps a. Use numpy.random.uniform(). b. Plot both the uniform distribution and the sample mean distribution for comparison.


# {index}`Discrete probability distribution`
When the probability varies across repetitions, the mean (the expected value) is determined by considering all possible values of the random variable, denoted as $x_i$. Each value is multiplied by its respective probability, $p_i$, and the products are then summed together.

$\text{mean} = \sum_i^{}p_ix_i$

$\text{variance} = \sum_i^{}p_i(x_i-\text{mean})^2$

If each of the individual probabilities, $p_i$, are plotted, the discrete probability distribution is called a **discrete probability density function** (or a probability mass function, PMF). A discrete random variable is one that can take on a countable number of distinct values. For each possible value of the random variable, the PMF gives the probability of observing that value.

This can be denoted as $P(X = x)$, where $X$ is the random variable and $x$ is a specific value that the random variable can take.
 
> Key properties of a discrete probability density function include:
> 
> 1. Non-negative values: $P(X = x) \geq 0$ for all possible values of $x$.
>
> 2. Sum of probabilities: The sum of the probabilities for all possible values of $x$ equals 1: $\sum_{\text{all } x} P(X = x) = 1$.
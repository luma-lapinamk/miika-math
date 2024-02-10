# {index}`Binomial distribution`
The binomial distribution is a discrete probability distribution that describes the number of positive outcomes in a fixed number of independent events, where each event has the same probability of success. In other words, it models the number of positive outcomes, denoted by $k$, out of a fixed number of independent events (or experiments), denoted by $n$, where each experiment can result in either success or failure.

> Key characteristics of the binomial distribution include
>
> - **Binary Outcomes**: Each event can result only in one of two outcomes: postivive or negative / success or failure / ture or false etc.
>
> - **Independent Trials**: The events are independent of each other, meaning the outcome of one event does not influence the outcome of another.
>
> - **Constant Probability**: The probability of success is constant for each event. In other words, the probability does not change between events.

The probability of event $A$ happening exactly $k$ times out of $n$ is given by the **discrete probability density function**, also knwon as the **mass function of the binomial distribution**, the **PMF**. The formula looks like

$P(A=k) = \binom{n}{k} p^k (1 - p)^{n - k}$, where

- $\binom{n}{x}$ is here called as the **binomial coefficient**, also known as the **k-combinations of n**, which represents the number of ways to choose $k$ successes out of $n$ events
- $p$ is the probability of success in each event
- $(1 - p$ is the probability of failure in each trial, sometimes denoted by $q = (1 - p)$ and
- $n$ is the total number of events.

So the formula can be interpretated kind of as the product of $\text{combinations} \times \text{successes} \times \text{failures}$.
<br></br>

**Example.** What is the probability of getting two times the value of 6 out of six casts?

Here $k=2$, $n=6$ and $p=\frac{1}{6}$. Let's substitute this in the discrete probability density function.

$\begin{align}P(A=2) &= \binom{6}{2} \cdot (\frac{1}{6})^2 \cdot (1 - \frac{1}{6})^{6 - 2} \\ \\
&= 15 \cdot \frac{1}{36} \cdot \frac{625}{1296} \\ \\
&= \frac{3125}{15552} \\ \\
&= 0.200 \ldots \end{align}$
<br></br>

The **mean** of the binomial distribution is given by

$\text{mean} = np$, where

- $n$ is the total number of events and
- $p$ is the probability of success in each event.

So, the product $np$ gives us the expected number of successes (or positive outcomes) in $n$ events.
<br></br>

The **variance** of the binomial distribution is given by

$\sigma^2 = np(1 - p)$

Variance describes how much the values vary from the mean, so it gives the spread of the distribution. If $p$ is close to 0 or 1, meaning the probability of success or failure is very low or very high, the variance tends to be smaller. If $p$ is closer to 0.5, indicating a more balanced probability of success and failure, the variance tends to be larger.
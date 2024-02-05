# {index}`Random phenomena`
All phenomena can, in principle, be divided into two groups.

- **Deterministic phenomena** are highly predictable, for example, based on the laws of physics. It is known that when a stone held in hand is released, it falls to the ground due to the influence of gravity.
- The outcome of a **random phenomenon**, on the other hand, cannot be precisely predicted in advance. When a six-sided die is thrown onto a table, it cannot be known in advance what number will appear on the die.

**Probability calculus** is the theory of mathematical models for random phenomena (random experiments). The following steps are associated with modeling:

1. Outline the options, or **elementary outcomes**, associated with a random experiment. The elementary outcomes are described with the precision necessary for the analysis. For example, in the toss of a six-sided dice, the elementary outcomes are considered to be the possible face numbers: 1, 2, 3, 4, 5, and 6. (The trajectory of the dice's roll is irrelevant for the analysis.) The set of all elementary outcomes is referred to as the **universal set** of the random experiment, denoted here by the letter $U$. So, in the case of a dice roll, $U = \{1, 2, 3, 4, 5, 6\}$.

2. In a random experiment, the realization of various events is observed. An **event** is a subset of the given set, and its elements are called **favourable elementary outcomes**. For example, in the toss of a six-sided dice, an event could be denoted as $A$ = 'the dice shows an odd number,' which corresponds to $A = \{1, 3, 5\}$. The favorable elementary outcomes for event $A$ are 1, 3, and 5.

3. Finally, in modeling, the probabilities of events must be determined.

An event also has a **complementary event**, known as the **complement**. For instance, for the event $A$ = 'the dice shows an odd number,' the complement is $\overline{A}$ = 'the dice does not show an odd number', or equivalently, 'the dice shows an even number', which can be expressed as $\overline{A} = \{2, 4, 6\}$.
> Events $A$ and $B$ are separate or **mutually exclusive** (complementary) when they cannot occur simultaneously, i.e., they have no common elementary outcomes.

Event $A$ and its complement $\overline{A}$ are always separate.

:::{admonition} Definition
The probability of an event $A$ is denoted as $P(A)$. The probability $P(A)$ must satisfy the following conditions:

a) The probability of any event $A$ is non-negative, i.e., $P(A) \ge 0$.

b) The probability of the certain event $U$ is one, i.e., $P(U) = 1$.

c) The probability of the impossible event $\emptyset$ is zero, i.e., $P(\emptyset) = 0$.

d) Probability is additive, meaning that if $A$ and $B$ are separate events, then the probability of the event $A$ or $B$ is $P(A \cup B) = P(A) + P(B)$.
:::

The probabilities of elementary outcomes are called **point probabilities**. If the probabilities of all elementary outcomes are equal, the elementary outcomes are symmetric.

**Example.** Let's consider a coin toss. In a coin toss, the elementary outcomes are heads and tails, so $E = \{ \text{heads, tails} \}$. It is reasonable to assume that the elementary outcomes are equally likely, and the pattern on the coin does not affect the probabilities of elementary outcomes. Therefore, the elementary outcomes occur with equal probability, making them symmetric.

When considering this mathematically, let $A$ = 'heads', $B$ = 'tails', and $E$ = 'heads or tails', which is a certain event. Let's determine the probabilities of the elementary outcomes or point probabilities $P(A)$ and $P(B)$. Since events $A$ and $B$ are separate, meaning they have no common elementary outcomes, according to additivity, we get

$\begin{align} P(A \cup B)&=P(A)+P(B) \\ \\
P(E)&=P(A)+P(B) \\ \\
1&=P(A)+P(B) \\ \\
1&=2P(A) \\ \\
P(A)&=\frac{1}{2} \end{align}$

Therefore $P(\text{heads})=P(\text{tails})=\frac{1}{2}$.
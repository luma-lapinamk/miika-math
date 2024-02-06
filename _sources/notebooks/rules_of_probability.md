# {index}`Rules of probability`
For starters...

Since the examples below deal with a standard 52-deck of cards, the four suits are spaces, hearts, clubs and diamonds, as seen in the figure below. Each suit includes 13 ranks: ten numeral cards (1 = Ace, 2, 3, ..., 10) and three face cards (King, Queen and Jack). Depending on a game, the ace can also have the rank of 14.

<p><a href="https://commons.wikimedia.org/wiki/File:Piatnikcards.jpg#/media/File:Piatnikcards.jpg"><img src="https://upload.wikimedia.org/wikipedia/commons/0/02/Piatnikcards.jpg" alt="Piatnikcards.jpg" height="360" width="770"></a><br><a href="https://creativecommons.org/licenses/by/3.0" title="Creative Commons Attribution 3.0">CC BY 3.0</a>, <a href="https://commons.wikimedia.org/w/index.php?curid=7104281">Link</a></p>

Basic rules of probability are **Addition rule** and **Complement rule**.

## {index}`Addition rule`
Depending on whether both events can occur at the same time, or does one event exclude the other, the addition rule can have two outcomes.

When events $A$ and $B$ cannot occur at the same time or they are mutually exclusive, the probabilites can be added together since the events are different cases.

$P(A \cup B)=P(A)+P(B)$

$P(A \ \text{or} \ B)=P(A)+P(B)$

```{figure-md} addition_rule
<img src="../images/probstat/addition_rule.png" alt="Addition rule" class="bg-primary mb-1" width="400px" align="center">

Separate elementary events are both counted since the other cannot happen if the other one does.
```

**Example.** A random card is picked from the deck. What are the odds that the card is either spaces or diamonds?

<br></br>

When events $A$ and $B$ can occur at the same time, or they have common elements, the same events would be counted twice. Therefore the union of $P(A)$ and $P(B)$ must be subtracted.

$P(A \cup B)=P(A)+P(B)-(P(A) \cap P(B))$

$P(A \ \text{or} \ B)=P(A)+P(B)-(P(A) \ \text{and} \ P(B))$

```{figure-md} addition_rule_conditional
<img src="../images/probstat/addition_rule_conditional.png" alt="Common elementary events are counted twice" class="bg-primary mb-1" width="300px" align="center">

Common elementary events are counted twice unless they are subtracted.
```

**Example.** A random card is picked from the deck. What are the odds that the card is spaces or a face card?

:::{admonition} EXERCISE 1. Two dices
:class: tip, dropdown
In a board game, two six-sided dices are cast. The player wins a prize, if the faces of the dice are the same or the sum of the faces is 7 or 11. If the player doesn't win the prize, the player can try once again. What is the probability that the player wins the prize?
:::

:::{admonition} EXERCISE 2. Oh no more balls!
:class: tip, dropdown
The are 7 red balls, 4 blue balls and 5 white balls in box. Two balls are randomly picked. What is the probability that the balls are red and white?
:::
<br></br>

## {index}`Complement rule`
Since an event $A$ and its complementary event $\overline{A}$ are separate and mutually exclusive events, based on the additivity of probabilities, we have that 

$\begin{align}P(A \cup \overline{A})&=P(A)+P(\overline{A}) \\ \\
1&=P(A)+P(\overline{A}) \\ \\
P(A)&=1-P(\overline{A})\end{align}$

If you know the chance of something occurring, then you can easily find the chance of it not occurring by subtracting the probability of it happening from 1, as the sum of the probabilities of an event and its complement is always 1. The complement rule can be spesifically useful in cases, where the question is about "at least" or "no more than".

**Example.** Three cards are picked from the deck. What are the odds that at least one card is a face card?

:::{admonition} EXERCISE 3. Birthday on same weekday
:class: tip, dropdown
What is the probability that at least two persons of four are born on the same weekday?
:::
<br></br>

## {index}`Conditional probability`
Conditional probability is probability of event $A$ happening given that event $B$ has already occurred, and it's denoted as $P(A|B)$. Mathematically, the conditional probability of event $A$ given event $B$ is calculated using the formula:

$P(A|B) = \frac{P(A \cap B)}{P(B)}$, where
- $P(A|B)$ is the conditional probability of event $A$ given event $B$.
- $P(A \cap B)$ is the probability of both events $A$ and $B$ occurring simultaneously (the intersection of $A$ and $B$).
- $P(B)$ is the probability of event $B$ occurring.

The idea behind conditional probability is that the probability of event A happening can change depending on whether event B has already occurred. It's like updating our knowledge or information about the situation.

## {index}`General multiplication rule`
Nostetaan korttipakasta kaksi korttia. Millä todennäköisyydellä molemmat kortit ovat ässiä?

Korttipakassa on 52 korttia, joista 4 on ässiä. Kun ensimmäinen ässä on nostettu, korttipakassa on 51 korttia, joista 3 on ässiä. Lasketaan todennäköisyys sille, että molemmat kortit ovat ässiä.
 
P(molemmat kortit ovat ässiä)
= P(ensimmäinen kortti on ässä JA toinen kortti on ässä)
= P(ensimmäinen kortti on ässä) · P(toinen kortti on ässä)

## {index}`Law of Total Probability`

## {index}`Bayes' theorem`

## {index}`Chain rule`
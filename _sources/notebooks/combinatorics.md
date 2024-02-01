# {index}`Combinatorics`
Combinatorics is a branch of mathematics that deals with counting, arrangement and combination of objects or elements. It focuses on studying the ways in which simple discrete objects can be organized, combined or chosen. For instance, it is pretty easy to compute the amount of numbers with three figures but it is much harder to find all the possible arrengements for a bookshelf.

## {index}`Multiplication principle`
also known as **Rule of product**. When making multiple consecutive choices, the total number of possibilities is obtained by multiplying the respective numbers of options available at each choice stage. Intuitively it can expressed as "if there are $a$ ways of doing something and $a$ ways of doing another thing, then there are $a \cdot b$ ways of performing both actions."

The principle can be described by a ladder model.

**Example.** A student has two knitted caps, two jumpsuits and three pairs of shoes. How many different sets of outfits can be created from these pieces of clothing?

```{figure-md} multiprinciple
<img src="../images/probstat/multiprinciple.png" alt="Number of different sets of clothes" class="bg-primary mb-1" width="600px" align="center">

The number of different sets of outfits can be computed from the bottom row of the ladder moddel.
```

The cap can be chosen in two different ways, the jumpsuit can be chosen from two different options and there are three different pairs of shoes. Using the multiplication principle we can compute the number of different sets by $2 \cdot 2 \cdot 3 = 12$.

:::{admonition} EXERCISE 1. 13 Premier League matches
:class: tip, dropdown
There are 13 Premier League matches happening on the upcoming Saturday and a gambler can choose the result of a match from three different options.
- 1: home team wins
- X: tie
- 2: away team wins

a) How many different football pools does there exist?

b) What if the number of matches is $n$?
:::


## {index}`Addition principle`
also known as **Rule of sum**. The overall number of options of which to choose from can be can be computed by adding the number of separated options. In general, if there are different cases with n<sub>1</sub> choices in Case 1, n<sub>2</sub> choices in Case 2, and so forth, then the overall number of options is the sum n<sub>1</sub> + n<sub>2</sub> + ... + n<sub>k</sub>. Intuitively it can expressed as that if we have $A$ number of ways of doing something and $B$ number of ways of doing another thing and we can not do both at the same time, then there are $A+B$ ways to choose one of the actions."

**Example.** Store number 1 has three different computers for sale, store number 2 has five different computers for sale and store number 3 has four different computers for sale of which one is the same as in store number 1. How many different computers are there to choose from?

Applying the addition principle, there are 3 + 5 + (4 - 1) = 11 computers to choose from, since one of them is sold in two different stores.

:::{admonition} EXERCISE 2. Three digit password
:class: tip, dropdown
You have forgotten your three digit password but you know that the digits of the password are capital letters and at most (no more than) one of them is a vowel.

The numbers of Finnish vowels is 8 (A-E-I-O-U-Y-Ä-Ö-Å) and the number of consonants is 20.

a) How many different **cases** are there when taking into consideration that at most one of the digits is a vowel?

b) How many different strings (ordered three digit sets) are there that matches of what you can remember about your password?

c) How many different strings are there all together?
:::

## {index}`Permutations and variations`

:::{admonition} Definition
Let *A* be a set of *n* elements. A **permutation** of *A* is any sequence of its elements, where every element of *A* appears exactly once.
:::

In short, a permutation is an ordered arrangement of things. 

**Example.** Let *A* = {*a*, *b*, *c*}. All the permutations of *A* are {*a*, *b*, *c*}, {*a*, *c*, *b*}, {*b*, *a*, *c*}, {*b*, *c*, *a*}, {*c*, *a*, *b*} and {*c*, *b*, *a*}.

```{figure-md} permutationladder
<img src="../images/probstat/permutationladder.png" alt="Number of permutations of a set {a, b, c}" class="bg-primary mb-1" width="600px" align="center">

The number of permutations of a set {*a*, *b*, *c*} can be computed from the ladder moddel. In the first step we have 3 options, in the second step we have 2 options and in the last step only one choice is possible for each sequence. The total amount of permutations can be computed using the multiplication principle: $3 \cdot 2 \cdot 1 = 6$.
```

Even words are permuations of a set of letters but only some sequences, for example, of letters A, C and R bear signifance: ARC and CAR. All the other arrangements are abbreviations of some sort. 

## {index}`Combinations`

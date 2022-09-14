# Sets of numbers
Set of **{index}`natural numbers`** is denoted as $\mathbb{N}=\left\{0{,}1{,}2{,}3{,}...\right\}$, sometimes called as the "naturals".
> Natural numbers without zero $\mathbb{N}^+=\left\{1{,}2{,}3{,}...\right\}$ are also called as counting numbers.

Set of **{index}`integers`** is denoted as $\mathbb{Z}=\left\{...{,}-3{,}-2{,}-1{,}0{,}1{,}2{,}3{,}...\right\}$
> Positive integers are denoted as $\mathbb{Z}^+=\left\{1{,}2{,}3{,}...\right\}$, which is actually the same set as $\mathbb{N}^+$. As a subset, this can be denoted as $\mathbb{N}^+\subseteq\mathbb{Z}^+$ and $\mathbb{Z}^+\subseteq\mathbb{N}^+$, since every number (*element*) of $\mathbb{N}^+$ is also a number (*element*) of $\mathbb{Z}^+$.

> Negative integers $\mathbb{Z}^-=\left\{...{,}-3{,}-2{,}-1\right\}=\mathbb{Z}\ \setminus\mathbb{N}$. Here the notation $\mathbb{Z}\ \setminus\mathbb{N}$ means that the numbers in the set of natural numbers are removed from the set of integers, i.e. the subtraction of sets.

:::{admonition} EXAMPLE 1. the number $4k-5{,}\ k\in\mathbb{Z}$ is always odd
:class: tip, dropdown
Proof:

$\begin{align} 4k-5 & =\left(4k-6\right)+1 \\ \\
& =2\left(2k-3\right)+1{,}\ k\in\mathbb{Z} \end{align}$

What we have shown is that the $2\left(2k-3\right)$ is always even for every value of $k$, because the coefficient in front of the brackets is $2$. Therefore $2\left(2k-3\right)+1=4k-5$ is always odd.

:::

**{index}`Rational numbers`** $\mathbb{Q}$, the "fractions", are denoted as

$\mathbb{Q}=\left\{\frac{m}{n}\mid\ m{,}n\ \in\mathbb{Z}{,}\ n\ne0\right\}$
> Includes numbers whose decimal expasion terminates, e.g $\frac{3}{5}=0.6$ or
> decimal expansion begins to repeat a finite sequence e.g. $\frac{13}{17}=0.76470588235294117647058823529411...$, where the repeating finite sequence is $7647058823529411$.

When numbers cannot be expressed as a ratio of two integers, they are called **{index}`irrational numbers`**. For instance $\sqrt{2}=1.414...$ and $pi{,}\ \pi=3.14159...$ are irrational numbers. Here decimal expansion does not terminate nor end with a repeating finite sequence.

**{index}`Real numbers`** $\mathbb{R}$ include rational and irrational numbers. We can call this as a *union* of rational and irrational numbers.
> Real numbers correspond to all the points on a number line.

**{index}`Complex numbers`** $\mathbb{C}$ can be expressed as a sum of a real part $a$ and an imaginary part $bi$ as $a+bi$, where $a{,}b\in\mathbb{R}$ and $i$ is the imaginary unit, which is denoted as  $i^2=-1\Leftrightarrow i=\sqrt{-1}$.
> The imaginary part $bi{,}\ b\in\mathbb{R}$ actually forms the set of imaginary numbers, in which real numbers are multiplied by the imaginary unit.

Every set of numbers is a "proper" subset of larger one, excluding the set of complex numbers: $\mathbb{N}\subset\mathbb{Z}\subset\mathbb{Q}\subset\mathbb{R}\subset\mathbb{C}$. This can be presented as an Euler diagram:

```{figure-md} Euler_diag
<img src="../images/algebra/Euler_diag.png" alt="Sets of numbers presented in an Euler diagram" class="bg-primary mb-1" width="600px" align="center">

Sets of numbers presented in an Euler diagram
```
- Natural numbers are a proper subset of integers.
- Integers are a proper subset of rational numbers.
- Rational numbers are a subset of the real numbers.
- Union of rational and imaginary numbers makes up the real numbers.
- Complex Numbers are the superset of all other sets.
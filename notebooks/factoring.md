# {index}`Factoring`
by constant and/or variable(s)

## Let's start with some examples

a) $6x^2-x=x(6x-1)$

b) $-8x^4+6=2(-4x^4+3)=-2(4x^4-3)$ Here both are considered valid answers.

c) $5xy^2-xy+9y=y(5xy-x+9)$

d) $\frac{9}{2}x^2+\frac{1}{2}x=x(\frac{9}{2}x+\frac{1}{2})=\frac{1}{2}x(9x+1)$

e) $-10a^2b^2+6a^2b-ab=ab(-10ab+6a-1)$

f) $20x^3+16x^2+4=4(5x^3+4x^2)+4=4(5x^3+4x^2+1)=4(x+1)(5x^2-x+1)$ **Only products are valid answers.**

## Factoring by division
for quadratic and higher degree of polynomials

Here is a link for the technique used in Finnish schools: <a href="https://opetus.tv/lukio-ops2016/matematiikka/maa2/polynomin-jakaminen-polynomilla-jakokulmassa/" target="_blank">Polynomin jakaminen polynomilla jakokulmassa | Opetus.tv</a>

### Examples
a) $P(x)=5x^2-10x-15$

Let's try to find a value for the variable x so that $P(x)=0$.

It turns out that if $x=-1$, then $P(x)=0$. This means that one factor of the polynomial $P(x)$ is $(x+1)$.

Then there are different techniques or algorithms to find out what the other factor will be. I (the author) use a method called a "division angle" since it is an algorithm and it doesn't need "trial and error".

<iframe width="560" height="315" src="https://www.youtube.com/embed/jNJeZlHsMHg?si=5vpWLdbyo49W-9_C" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

We found that the second factor is $(5x-15)$, so the polynomial can be factorized as

$P(x)=(x+1)(5x-15)$

But this can be factorized even further! The final answer is $P(x)=5(x+1)(x-3)$ so always remember to factorize as far as possible. With polynomials of higher degree, you have to continue to find out other factors as well.<br><br>

b) $P(x)=-x^2+4x-3$

One solution for $P(x)=0$ would be $x=1$, since $P(1)=-1^2+4\cdot 1-3=0$. Therefore one factor of $P(x)$ is $x-1$. Let's find the oher factor.

<iframe width="560" height="315" src="https://www.youtube.com/embed/B_NBi4cezd8?si=fvpxlGM7V7ncWGqh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

So $P(x)=-x^2+4x-3=(x-1)(-x+3)$.

## Polynomials with higher degree

Same algorithm works here: if one value for the variable $x$ is $k$ so that $P(k)=0$, then the polynomial with a degree of $n$ will be factored to $(x-m)$ and to a polynomial with a degree of $n-1$. Then continue to factor out the polynomial with a degree of $n-1$ as well.

### Examples
a) $P(x)=x^3+2x^2+3x+6$

b) $Q(x)=2x^3+5x^2-36x+36$

c) $R(x)=4x^4+14x^3-62x^2+72$

## Special forms of polynomials

Here are some useful special forms of polynomials.

The Square of a Binomial

$\begin{align} I) \ (x+y)^2&=x^2+2xy+y^2, \ \text{which means that usually that} \ x^2+y^2\ne(x+y)^2 \\
II) \ (x-y)^2&=x^2-2xy+y^2 \\ \\
III) \ x^2-y^2&=(x+y)(x-y) \\
IV) \ x^3+y^3&=(x+y)(x^2-xy+b^2) \\
V) \ x^3-y^3&=(x-y)(x^2+xy+y^2 \end{align}$

### Examples
a) $A(x)=6x^2+12x+6$

b) $B(x)=x^2+10xy+25y^2$

c) $C(y)=4y^2-16y+16$

d) $D(x)=16x^2-9$

e) $E(x)=25-x^2$

f) $F(x)=8x^3+27$

g) $R(x)=4x^4+14x^3-62x^2+72$

## Factoring by gouping

Factoring of quadratic polynomials of the form of $P(x)=ax^2+c$ can be factored, if possible, by using the special form of $x^2-y^2=(x+y)(x-y)$.

For complete quadratic polynomials of the form of $P(x)=ax^2+bx+c$ a technic called **grouping** is an effective way. For example, let $P(x)=5x^2+9x-2$. Now we have to solve a pair of equations that satisfies these two conditions:

When $ab=5\cdot(-2)=-10$ and $b=9$, then

$\begin{align} kl&=-10 \\
k+l&=9\end{align}$

To work this out, we have to find such integers $k$ and $l$ so that their product equals -10 and their sum equals 9. We can do this by writing down all the possible combinations of $k \cdot l$ that produces -10.

$\begin{align} 1\cdot(-10)&=-10 \\
-1\cdot10&=-10 \\
2\cdot(-5)&=-10 \\
-2\cdot5&=-10\end{align}$

From the combinations we can see that $-1+10$ is equal to $9$, so that is our solution. Now we can write $\textbf{\emph{9x=-x+10x}}$ and substitute that in the polynomial.

$\begin{align}5x^2+\textbf{\emph{9x}}-2&=5x^2\textbf{\emph{-x+10x}}-2 \\
&=x(5x-1)+2(5x-1) \\
&=(5x-1)(x+2)\end{align}$
<br>

### Another example

Let $Q(x)=5x^2+11x-12$. This time $k \cdot l=5\cdot(-12)=-60$

$\begin{align} -1\cdot60&=-60 \\
-2\cdot30&=-60 \\
-3\cdot20&=-60 \\
-4\cdot15&=-60 \end{align}$

From the last combination we can now pick $k+l=-4+15=9$. Therefore

$\begin{align}5x^2+11x-12&=5x^2-4x+15x-12 \\
&=5x^2+15x-4x-12 \ (\text{This time we had to change the order of} \ k \ \text{and} \ l) \\
&=5x(x+3)-4(x+3) \\
&=(x+3)(5x-4) \end{align}$

Here is little video of the solution.
<iframe width="560" height="315" src="https://www.youtube.com/embed/BZgkpBQMqww?si=rRxmE_zGZcIct8Bt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<br>
And finally, couple of harder examples to look into.

$\begin{align}\text{a)} \ 2x^4-3x^3+2x-3&=2x^4+2x-3x^3-3 \\
&=2x(x^3+1)-3(x^3+1) \\
&=(x^3+1)(2x-3)\end{align}$

$\begin{align}\text{b)} \ x^5-2x^3-4x^2+8&=x^3(x^2-2)-4(x^2-2) \\
&=(x^2-2)(x^3-4)\end{align}$
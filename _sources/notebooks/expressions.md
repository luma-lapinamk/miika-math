# Expressions

## Preface
Distance, length, width, all are one dimensional quantities and their magnitude is expressed in many different units. The one used in {index}`International System of Units`, the SI-system, is metre. For instance a classroom can have a width of 12 metres and a length of 14 metres. This means that the classroom is twelve times as wide as on metre. Metres can be expressed shorter as a symbol m.

We can add and subtract metres. For instance the perimeter of the classroom can be calculated as
$\mathrm{12\ m+14\ m+12\ m+14\ m}$.

If we want, this can be rearranged as

$\begin{align} &\mathrm{12\ m+12\ m+14\ m+14\ m} \\
&\mathrm{=2\cdot12\ m+2\cdot14\ m} \\
&\mathrm{=2\cdot(12\ m+14\ m)}\end{align}$

We can also see that the length of the classroom is two meters greater than it's width. This can be presented as

$\text{lenght}-\text{width}=\mathrm{14\ m-12\ m=(14-12)\ m=2\ m}$

When we talk about terms, their addition and subtraction are not that different but we must pay attention to which of the terms are like.

Let's go back to our classroom example and calculate it's area.

$\begin{align}12\ \mathrm{m}\cdot 14\ \mathrm{m} &=12\cdot 14\cdot \mathrm{m}\cdot \mathrm{m} \\
&= 168\ \mathrm{m^2} \end{align}$

It's clear that the unit is now different and that we cannot add width and area together as we can add width and length. This means that the width and length are **like quantities** but width and area are **unlike quantities**. However, we can multiply the area by the height and get the volume of the classroom. Still, length, area and volume are all unlike quantities and addition and subtraction of these quantities is not possible: $\mathrm{12\ m+168\ m^2}$ doesn't "add up".

## Terms
A {index}`term` has it's coefficient and a variable. Coefficient can be any scalar $a\in\mathbb{R}$ and we can use what ever symbol to denote the variable, but usually $x$ is used. For instance $4x{,}\ 7x{,}-2x^3{,}\ 9$ and $3xy$ are all terms, where 9 is a numerical term called a constant.

Only like terms can be combined. Of the terms mentioned above, only terms $4x$ and $7x$ are like and we can combine them by addition or subtraction.

Addition: $4x+7x=\left(4+7\right)x=11x$ "4 apples plus 7 apples equals 11 apples."
Subtraction: $4x-7x=\left(4-7\right)x=-3x$ "if there are 4 apples and 7 apples are needed, 3 apples will be missed."

Multiplication and division can be done to all terms. For instance

$4x\cdot7x=4\cdot7\cdot x\cdot x=28x^2$

$4x\cdot3xy=4\cdot3\cdot x\cdot x\cdot y=12x^2y$

$\frac{4x}{9}=\frac{4}{9}x$ variable x remains

$\frac{4x}{7x}=\frac{4}{7}$ variable x is reduced

## Expressions
Algebraic expressions are simplified combinations of unlike terms separated by + and - sings. Of the terms mentioned above, we can write expressions like 

$4x+9$

$7x+3xy$

$7x-2x^3+9$ but here the terms are not arranged correctly. Always write expressions as of lowering order of power! (The highest power first, then the second highest and so forth and constant last.) The correct expression is $-2x^3+7x+9$.

In Physics, expressions are called **formulas**. Here are some examples.

Area of an triangle $\mathrm{A=\frac{1}{2}\text{base}\cdot\text{height}=\frac{1}{2}bh}$'

$\text{miles} =1.6\cdot\text{kilometres}$

Distance $\mathrm{s=\frac{1}{2}\text{acceleration}\cdot\text{time}^2=\frac{1}{2}at^2}$

Temperature in Kelvin $\mathrm{K=°C+273}$

Formulas are typically used to evaluate the value of a unit. So can expressions also be evaluated, when variables are given a value.

### And a bit more

It is good to know these {index}`squares of binomials`

$\begin{align}(x+y)^2&=(x+y)(x+y) \\
&=x(x+y)+y(x+y) \\
&=x\cdot x+x\cdot y+y\cdot x+y\cdot y \\
&=x^2+xy+yx+y^2 \\
&=x^2+2xy+y^2\end{align}$

$\begin{align}(x-y)^2&=(x-y)(x-y) \\
&=x(x-y)-y(x-y) \\
&=x\cdot x+x\cdot(-y)-y\cdot x-y\cdot(-y) \\
&=x^2-2xy+y^2\end{align}$

and the product of a sum and a difference

$\begin{align}(x+y)(x-y)&=x(x-y)+y(x-y) \\
&=x\cdot x+x\cdot(-y)+y\cdot x+y\cdot(-y) \\
&=x^2-xy+xy-y^2 \\
&=x^2-y^2\end{align}$

**Examples**

a) $(2x+5)^2$ with steps

$\begin{align}(2x+5)^2&=(2x+5)(2x+5) \\
&=2x(2x+5)+5(2x+5) \\
&=2x\cdot2x+2x\cdot5+5\cdot2x+5\cdot5 \\
&=2\cdot2\cdot x\cdot x+10x+10x+25 \\
&=4x^2+20x+25\end{align}$

$(2x+5)^2$ with formula

$\begin{align}(2x+5)^2&=(2x)^2+2\cdot2x\cdot5+5^2 \\
&=4x^2+20x+25\end{align}$


b) $(-3a-7b)^2$  with steps

$\begin{align}(-3a-7b)^2&=(-3a-7b)(-3a-7b) \\
&=-3a(-3a-7b)-7b(-3a-7b) \\
&=-3a\cdot(-3a)-3a\cdot(-7b)-7b\cdot(-3a)-7b\cdot(-7b) \\
&=3\cdot3\cdot a\cdot a+21\cdot a\cdot b+21\cdot b\cdot a+7\cdot7\cdot b\cdot b \\
&=9a^2+42ab+49b^2\end{align}$

$(-3a-7b)^2$  with formula

$\begin{align}(-3a-7b)&=(-3a)^2-2\cdot(-3a)\cdot7b+(-7b)^2 \\
&=9a^2+42ab+49b^2\end{align}$


c) $(4x+1)(4x-1)$ with steps

$\begin{align}(4x+1)(4x-1)&=4x(4x-1)+1(4x-1) \\
&=4x\cdot4x-4x\cdot1+1\cdot4x-1\cdot1 \\
&=4\cdot4\cdot x\cdot x-4x+4x-1 \\
&=16x^2-1\end{align}$

$(4x+1)(4x-1)$ with formula

$\begin{align}(4x+1)(4x-1)&=(4x)^2-1^2 \\
&=4^2x^2-1\cdot1 \\
&=16x^2-1\end{align}$


**The {index}`law of distributive`** $a\cdot(b+c)=a\cdot b+a\cdot c$
is very useful in finding a common coefficient.

For instance

a) $4a+ab=a(4+b)$

b) $2xy-5yz+y=y(2x-5z+1)$

c) $-11x-8=-1(11x+8)=-(11x+8)$

d) $ax+ay+bx+by=a(x+y)+b(x+y)=(x+y)(a+b)$
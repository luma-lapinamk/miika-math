# Quadratic functions

(figures are missing)

Quadratic functions in the form of $f(x)=ax^2+bx+c$, where $a,b,c ∈ℝ$, are parabolas when poltted in (x,y)-plane.

For example

a) $f(x)=3x^2-4x+1$ multiplies variable $x$ squared by three, subtracts $x$ multiplied by four and adds one. 

The values can be computed depending on the value of variable $x$, for instance

$f(-1)=3\cdot(-1)^2-4\cdot(-1)+1=8$

$f(0)=3\cdot0^2-4\cdot0+1=1$

$f(1)=3\cdot1^2-4\cdot1+1=0$

$f(2)=3\cdot2^2-4\cdot2+1=5$

> - if $a < 0$, the parabola opens downwards, "a cap"
> - if $a > 0$, the parabola opens upwards, "a cup"
> - if $a = 0$, the functions becomes a linear function

<br>

Example. Solve $f(x)=10$.

$\begin{align}3x^2-4x+1=&10 \\
3x^2-4x-9=&0 \end{align}$

Using the quadratic formula

$\begin{align}x=&\frac{-b\pm\sqrt{b^2-4ac}}{2a} \\
x=&\frac{-(-4)\pm\sqrt{(-4)^2-4\cdot3\cdot(-9)}}{2\cdot3} \\
x=&\frac{4\pm\sqrt{124}}{6} \\
x=&\frac{4\pm\sqrt{124}}{6} \\
x=&\frac{4\pm2\sqrt{31}}{6} \\
x=&\frac{2\pm\sqrt{31}}{3} \end{align}$

<br>

**How to find the roots?**

When a function intersects the x-axis, the value of the function is 0. So the root can be found by solving an equation of $f(x)=0$ by factoring or using the quadratic formula.

$\begin{align}f(x)=&0 \\
3x^2-4x+1=&0 \\
x=&\frac{-b\pm\sqrt{b^2-4ac}}{2a} \\
...& \\
x=&\frac{1}{3} \ \text{or} \ x=1 \end{align}$


The number of roots can be solved from the discriminant, $D=b^2-4ac$

> - if $D > 0$, the function has two roots
> - if $D = 0$, the function has one root and the root is at the same point as the vertex and root is $x=-\frac{b}{2a}$
> - if $D < 0$, the function has no roots

## Minimun and maximum

The minimum and maximum value of the function can be found from the vertex or from the end points of a specific closed domain.

Let's examine the function $f(x)=3x^2-4x+1$.

Since $a > 0$, the parabola opens upwards (cup). Therefore, the minimum value can be found from the vertex using formula of $x=-\frac{b}{2a}$.

$x=-{\frac{-4}{2\cdot3}}=\frac{2}{3}$

Therefore the minimum is

$\begin{align}f(\frac{2}{3})=&3\cdot(\frac{2}{3})^2-4\cdot\frac{2}{3}+1 \\
=&3\cdot\frac{4}{9}-\frac{8}{3}+1 \\
=&\frac{4}{3}-\frac{8}{3}+1 \\
=&-\frac{1}{3} \end{align}$

Maximum value doesn't exists, because $a > 0$ UNLESS whe define the domain i.e. $x ∈ [0,4]$ (or using inequality: $0 ≤ x ≤ 4$). In this case, the vertex is in the domain!

Let's compute the value of our function in the points of the domain:

$f(0)=3\cdot0^2-4\cdot0+1=1$

$f(4)=3\cdot4^2-4\cdot4+1=33$

So the function has a maximum when $x = 4$ and the maximum is 33.

<br>

Example of an open domain of $]-1,1]$ (which is the same as $-1 < x ≤ 1$) . 

Let $gt(x)=-2x^2+6x-4{,}\ x\in]-1{,}1]$. Find the minimum and maximum.

The vertex is in

$x=-\frac{b}{2a}=-\frac{6}{2\cdot(-2)}=\frac{3}{2}$, which doesn't belong in the domain.

We can only find the value of the function in the end point of x = 1.

$g(1)=-2\cdot1^2+6\cdot1-4=0$

but we have to look at the point x = -1 as well.

$g(-1)=-2\cdot(-1)^2+6\cdot(-1)-4=-12.$

Concluding from the values of the function in the end points of the domain, the function has a maximum of 0 but no minimum.

The range is from minimum to maximum and in this case the range is $]-12,0]$ (which is the same as
-12 < x ≤ 0).

<br>

>The set of all possible inputs of a function is called a domain. In other words, domain corresponds to the values of the variable x.

>The set of all possible outputs of a function is called a range. In other words, range corresponds to the values that the function can have.
# Parallel vectors

:::{admonition} Definition
:class: seealso
Two non-zero vectors are parallel if one of the vectors can be presented as scalar multiplication of the other.

If $\overline{u}\parallel\overline{v}$, then $\overline{u}=r\overline{v}$, where $r \ne 0$.

If such a scalar doesn't exist, vectors are nonparallel, $\overline{u}\nparallel\overline{v}$.
:::

:::{admonition} EXAMPLE 1. **{index}`Parallel vectors`**
:class: tip, dropdown
Let's examine if vectors $\overline{u}=(6, -4)$ and $\overline{v}=(-\frac{1}{2},\frac{1}{3})$ are parallel.

We have to find if such a scalar $r$ exists so that $\overline{u}=r\overline{v}$.

$$\begin{align}(6, -4) & =r(-\frac{1}{2},\frac{1}{3}) \\ \\
(6, -4) & =(-\frac{1}{2}r,\frac{1}{3}r) \end{align}$$

Now we can write two equations corresponding the two components.

$$\begin{align}6 & =-\frac{1}{2}r & -4 & =\frac{1}{3}r \\ \\
r & =-12 & r & =-12 \\ \\
\end{align}$$

We have found such a scalar $r$ that satifies $\overline{u}=r\overline{v}$ so vectors are parallel. In fact, vectors are in the opposite directions since $r < 0$.

:::

We can also examine the parallelism of two vectors by forming their unit vectors and comparing the unit vectors components.

# Unit vector (kesken)

Sometimes it is necessary to form a **{index}`unit vector`** $\overline{a}^0$ of a given vector $\overline{a}$. The unit vector has the same direction as the original vector but its magnitude is 1. Unit vector of formed by dividing a vector by its magnitude. In practise, every component of a vector will be divided separately. Here is an example of a 3D-vector.

$$\begin{align}\overline{a}^0 & =\frac{\overline{a}}{\left|\overline{a}\right|} \\ \\
& =\left(\frac{a_x}{\left|\overline{a}\right|},\frac{a_y}{\left|\overline{a}\right|},\frac{a_z}{\left|\overline{a}\right|}\right) \\ \\
\end{align}$$

:::{admonition} EXAMPLE 2. Pisteeseen C asennetaan 30 m pitkä taulu alemman aidan AB suuntaisesti. Laske taulun toisen päätepisteen D koordinaatit.
:class: tip, dropdown
Kuva 1. 23 Esimerkki yksikkövektorin hyödyntämisestä

Huom! Pisteen C koordinaatteihin ei saa suoraan lisätä arvoa 30. Tämä veisi pisteen D väärään suuntaan suoraan koilliseen.
Muodostetaan ensin vektori \overline{AB}=\overline{OB}-\overline{OA}=\left(400,140\right)-\left(40,100\right)=\left(360,40\right). Jotta pisteestä C päästään 30 m vektorin \overline{AB} suuntaisesti, muodostetaan ensin vektorin \overline{AB} yksikkövektori.
{\overline{AB}}^0=\frac{\overline{AB}}{\left|\overline{AB}\right|}=\frac{\left(360,\ 40\right)}{\sqrt{{360}^2+{20}^2}}=\frac{\left(360,\ 40\right)}{40\sqrt{82}}
\ \ \ \ \ \ \ \ \ =\left(\frac{360}{40\sqrt{82}},\ \frac{40}{40\sqrt{82}}\right)=\left(\frac{9}{\sqrt{82}},\ \frac{1}{\sqrt{82}}\right)
\ \ \ \ \ \ \ \ \ =\left(0.993\ldots,0.110\ldots\right)

Seuraavaksi kerrotaan yksikkövektori pituudella 30, jotta saadaan siirtymävektori pisteiden C ja D välille.
\overline{CD}=30\bullet{\overline{AB}}^0=30\bullet\left(\frac{9}{\sqrt{82}},\ \frac{1}{\sqrt{82}}\right)=\left(\frac{270}{\sqrt{82}},\ \frac{30}{\sqrt{82}}\right)

Täten paikkavektori \overline{OD}=\overline{OC}+\overline{CD}=\left(40,130\right)+\left(\frac{270}{\sqrt{82}},\ \frac{30}{\sqrt{82}}\right)
\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ =\left(69.816\ldots,133.312\ldots\right)\approx\left(70,133\right) eli piste D = (70, 133).

:::


Esimerkki. 
 


# Preface
Vector, as a mathematical object, is only about 200 years old term. Initially one may come across with vectors as quantities in geometry, space and physics. Therefore computer models about real world and game engines rely on vectors. Vectors are also used in many branches of technology such as GPS localisation, image and graphics prosessing, robotics and of course, machine learning.

## Basic concepts

**{index}`Scalar`s** are described solely by their magnitude but **Vectors** also have **direction**. For instance speed, acceleration and force are vectors. In cartesian coordinate system, also know as the **(*x*, *y*)-coordinate system** or **plane**, vectors can describe the number of steps taken horizontally and vertically. The direction can also be to negative.
However, the location of a vector is not defined by in its definition. A vector can ne used describe the shortest route between two coordinate points. When a vector is defined this way, we use the term **displacement vector**.
<br>
<br>
<iframe scrolling="no" title="ENG - Siirtymävektori" src="https://www.geogebra.org/material/iframe/id/wnmjpae3/width/700/height/500/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/false/rc/false/ld/false/sdz/false/ctl/false" width="700px" height="500px" style="border:0px;"> </iframe>

:::{admonition} Instructions
You can move the beginning point *A*, **the tail**, and the ending point *B*, **the head**, of the displacement vector $\overline{AB}$ with your mouse and see how the components of the vector change.
:::
<br>

Vectors are comprised by two **components** in the cartesian plane just as coordinate points are. Where coordinate points describe the exact location of a single point, the components of a vector describe its length correspondingly. In the applet above the displacement vector from point A to point B is comprised of the component parallel to the *x*-axis (<font color="green">green dashed arrow</font>) and of the component parallel to the *y*-axis (<font color="red">red dashed arrow</font>). The components of the displacement vector are expressed in brackets as $\overline{AB}=(x, y)$. Vectors can also be described in the **polar coordinate system** or as a **single column or row matrix**, and these will be handled later in the material.


:::{admonition} Definition, angles
:class: seealso
**Direction angle** $\theta$ of a vector is measured to the **counterclockwise** direction from the positive *x*-axis.

An angle between two vectors (between 0° … 180°) is defined so that the tail of the two vectors is in the same coordinate point and the angle is measured **counterclockwise**.
```{figure-md} vector_angles
<img src="../images/vektorit/ENGsuuntakulma.png" alt="The direction angle and the angle between vectors" class="bg-primary mb-1" width="600px" align="center">

Examples of the direction angle and the angle between vectors
```

:::

### Of denoting

Vectors are usually denoted with a lower case letter with an overline (or a bar), for instance $\overline{u}$, $\overline{v}$, $\overline{w}$. In the case of a displacement vector, vectors are usually denoted by their tail and head coordinate points as $\overline{AB}$. An arrow above the letter $\vec{u}$ or letters $\vec{AB}$ is also used. In order to denote vectors in a fast way, letters can be written simply in bold, for instance **u** or **AB**. In this study material vectors are denoted with an overline and coordinate points are denoted by capital letters, for instance the origin is denoted as $O = (0, 0)$.
- Length of a vector is denoted as absolute value $|\overline{u}|$ or $|\overline{AB}|$
- When vectors are diverging, $\overline{u}\nparallel\overline{v}$ is used
- When vectors are perpendicular, $\overline{u}\perp\overline{v}$ is used
- When vectors are parallel, $\overline{u}\|\overline{v}$ is used (note: this can mean that the vectors are in the same direction or the opposite direction)
- Vectors are in the same direction $\overline{u}\uparrow\uparrow\overline{v}$
- Vectors are in the opposite direction $\overline{u}\uparrow\downarrow\overline{v}$

```{figure-md} vectors_in_plane
<img src="../images/vektorit/vektoreita.png" alt="Examples of vectors in a plane" class="bg-primary mb-1" width="600px" align="center">

Examples of vectors in a plane
```
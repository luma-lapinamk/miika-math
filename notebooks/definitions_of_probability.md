# {index}`General definitions of probability`
For introduction, let's compare how statistical and classical probabilites relate to each other.

<iframe fullscreen="" height="550px" scrolling="no" src="https://www.geogebra.org/material/iframe/id/humATwzb/width/750/height/550/border/000000/rc/false/ai/false/sdz/false/smb/false/stb/false/stbh/false/ld/false/sri/false" style="border: 0px;" width="750px"> </iframe>

Source: <a href="https://ggbm.at/humATwzb" target="_blank">Huippu, Otava</a>

## {index}`Statistical definition of probability`
Probabilities can be calculated based on experimental observations. The simplest example of such a probability is based on empirical or experimental data, known as **statistical probability**. In this case, the probability of an event is the same as the relative frequency of the corresponding statistical variable.

:::{admonition} Definition
Statistical definition of probability is denoted by
$P(A)=\frac{f_A}{n}$
where $f_A$ is the frequency of the event and $n$ is the number of observations.
:::

:::{admonition} EXERCISE 1. Statistics of Darts
:class: tip, dropdown
A dartboard is a circular ring target, where in the center of the board is a circle with a point value of 10. Surrounding this circle are numbered rings from 9 to 1, as well as an unnumbered border.

<p><a href="https://commons.wikimedia.org/wiki/File:Tikkataulu.JPG#/media/Tiedosto:Tikkataulu.JPG"><img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/Tikkataulu.JPG" alt="Tikkataulu.JPG" height="480" width="457"></a><br><a href="https://creativecommons.org/licenses/by-sa/3.0" title="Creative Commons Attribution-Share Alike 3.0">CC BY-SA 3.0</a>, <a href="https://commons.wikimedia.org/w/index.php?curid=8103163">Linkki</a></p>

Below are statistics of some darts practise.
```{figure-md} darts
<img src="../images/probstat/darts.png" alt="Statistics of darts practise" class="bg-primary mb-1" width="200px" align="center">

Statistics of 50 darts throws.
```
What is the probability that the score of a single throw is even?

:::

:::{admonition} EXERCISE 2. Jari 'The King' Litmanen #10
:class: tip, dropdown
The greatest Finnish football player is undisputedly Jari Litmanen. The probability that Litmanen scores once in a match 30 % and twice is 10 %. However, Litmanen doesn't score more than twice. What is the probability that Litmanen scores at least once in a match?
:::

## {index}`Classical definition of probability`
The classical definition of probability is based on equally likely outcomes in a universal set. According to this definition:

$P(A) = \frac{\text{number of favorable outcomes for event A}}{\text{total number of possible outcomes}}$

This definition assumes that all outcomes in the sample set are equally likely. It is commonly used in situations where each elementary outcome is equally likely to occur, such as in the tossing of a fair coin or a six-sided dice.

:::{admonition} EXERCISE 3. Balls in a box
:class: tip, dropdown
There are 4 blue, 1 yellow, and 3 red balls in a box. One ball is randomly drawn from the box. What is the probability that the ball is
a) blue
b) yellow
c) not red?
:::

:::{admonition} EXERCISE 4. Dial Home Device from Stargate
:class: tip, dropdown
A Dial Home Devices (DHD in short) is device that consist of 19 glyphs on the inner circle and 19 glyphs on the outer circle as well. The device opens a wormhole to a distant planet in our galaxy, where, let's say, one million planets are habitable and have a stargate.

![Dial Home Device from Stargate](https://static.wikia.nocookie.net/stargate/images/0/02/DHD.jpg/revision/latest/scale-to-width-down/1000?cb=20070513011315 "DHD")

To dial an address, seven glyphs must be pressed in a spesific order and one glyph can be selected only once.

What is the possibility that a randomly chosen address will open a wormhole to a planet?
:::

## {index}`Geometrical definition of probability`
For introduction...

<iframe fullscreen="" height="550px" scrolling="no" src="https://www.geogebra.org/material/iframe/id/xgTuTpJX/width/750/height/600/border/000000/rc/false/ai/false/sdz/false/smb/false/stb/false/stbh/false/ld/false/sri/false" style="border: 0px;" width="750px"> </iframe>

Source: <a href="https://www.geogebra.org/m/SUPFr8qC#material/xgTuTpJX" target="_blank">Huippu, Otava</a>

:::{admonition} EXERCISE 5. Stone is thrown
:class: tip, dropdown
A stone is being randomly thrown on an area of land, which has the shape of a rectangle and the dimensions are 4 metres and 6 metres. In the middle of the area is a circular pond with the radius of 2 meters. What is probability that the stone hits the pond?
:::

:::{admonition} EXERCISE 6. Darts - again
:class: tip, dropdown
<p><a href="https://commons.wikimedia.org/wiki/File:Tikkataulu.JPG#/media/Tiedosto:Tikkataulu.JPG"><img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/Tikkataulu.JPG" alt="Tikkataulu.JPG" height="480" width="457"></a><br><a href="https://creativecommons.org/licenses/by-sa/3.0" title="Creative Commons Attribution-Share Alike 3.0">CC BY-SA 3.0</a>, <a href="https://commons.wikimedia.org/w/index.php?curid=8103163">Linkki</a></p>

The diameter of the dartboard is 341 mm, measured from the outer edge of the number one (1). The diameter of the ten (10) is 35 mm, and the width of the rings is 17 mm.

Let's assume in questions a) and b) that the darts will hit some number.

a) What is the probability that a randomly thrown dart will hit at least nine?

b) Five darts are thrown on each turn. What is the probability that the total points of a turn is at least 45?

c) The possibility to miss the dartboard is 5 %. What is the probability that all five darts will hit at most two?
:::
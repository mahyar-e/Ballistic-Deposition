# Ballistic-Deposition
Ballistic deposition is one of the models of layer growth in material sciences. In this code I used python to simulate ballistic deposition on a 2d surface and the values of the scaling exponents are calculated.

The algorithm of simulation is this:

Suppose we have a 2d surface and some little parts of  mass are being dropped on the surface form above randomly (from +y direction downward). Each pixel represnts the tiny bit of mass. The particle begins its fall and sticks to the nearest pixel i.e. the left or right column (if its occupied).

Here is a link to the [surface growth wikipedia](https://en.wikipedia.org/wiki/Surface_growth)

Here is the ruslt for 100 particles falling on surface with width of 100 pixels:

![download](https://github.com/mahyar-e/Ballistic-Deposition/assets/78594407/5e837b82-03cf-49e6-956a-3557ffbe11b5)



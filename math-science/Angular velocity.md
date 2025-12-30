Given a mass point traveling in a circular motion with radius $r$ (m) and velocity $v$ (m/s), the ***angular velocity*** (rad/s) is the following vector:
$$
\omega = \frac{r \times v}{\lVert r \rVert^2}
$$
where $r$ is the vector from the origin to the mass point.

### Derivation
Let $\phi(t)$ be the angle (rad) swept by the circular motion at time $t$. Then the position of the mass point may be described by the following function:
$$
x = r\cos(\phi(t))i + r\sin(\phi(t))j
$$
Then velocity is the first derivative of the position function:
$$
v = -r \frac{d\phi}{dt}\sin(\phi(t))i + r\frac{d\phi}{dt}\cos(\phi(t))j
$$
Hence, the angular speed is
$$
\frac{d\phi}{dt} = \frac{\lVert v \rVert}{r}
$$
We define *angular velocity* as the following unit vector scaled by angular speed.
$$
\frac{r \times v}{\lVert r \times v \rVert}
$$
This yields
$$
\omega = 
\frac{d\phi}{dt}
\frac{r \times v}{\lVert r \times v \rVert} =
\frac{r \times v}{\lVert r \rVert^2}
$$
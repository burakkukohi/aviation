Given an object of mass $m$ (kg) traveling in a circle of radius $r$ (m) at a constant speed $v$ (m/s), the ***centripetal force*** (N) can be calculated by the formula:
$$
F = mv\omega = \frac{mv^2}{r}
$$
where where $\omega = \frac{v}{r}$ (rad/s) is the *angular speed*.

### Derivation
Fix a coordinate system so that the object travels counterclockwise with the velocity pointing in the positive $j$ direction at time 0, the momentum of the object can be described by the following function:
$$
p = -mv\sin(\omega t)i + mv\cos(\omega t)j
$$
Then the force is the first derivative of the momentum:
$$
F = -mv\omega\cos(\omega t)i - mv\omega\sin(\omega t)j
$$
Hence, the (2-)norm of the force is
$$
\lVert F \rVert_{2} = mv\omega = \frac{mv^2}{r}
$$
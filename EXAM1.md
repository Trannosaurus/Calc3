# Vector Projections & Orthogonal Components
Given to vectors u and v, we can find the projection of them and an orthogonal vector
## Formula for Projection

$$
\text{proj}_\mathbf{u}\mathbf{v} = \frac{\mathbf{v} \cdot \mathbf{u}}{\|\mathbf{u}\|^2} \mathbf{u} = \frac{{v_1u_1 + v_2u_2 + v_3u_3}}{{u_1^2 + u_2^2 + u_3^2}} \begin{bmatrix} u_1 \\ u_2 \\ u_3 \end{bmatrix}
$$

## Orthogonal
Once we have the result of the projection, lets call it $w_1$,
the orthoganal vector, $w_2$, will be the vector we are projecting - $w_1$, so in this case

$$
w_2 = v - w_1
$$

# Distance from Point to Line
## Components to solving this

$$
P_0 = \text{{Starting point of the line}}
$$

$$
P = \text{{The point we are trying to find the distance to}}
$$

$$
L = \text{{The vector for the line}}
$$

$$
Q = \text{{A point on the line such that }} \vec{PQ} \perp L
$$

## Formula
$$
\text{distance} = \frac{{\lVert \vec{P_0P} \times \mathbf{L} \rVert}}{{\lVert \mathbf{L} \rVert}}$$

# Distance from planes to a point
## Planes
To define a plane, you need to have a point and a vector thats perpendicular to the plane known as the normal vector.
### Finding the Equation of a Plane given three points
Given three points, you can find the normal vector by taking the cross product of two vectors made from the three points
> **_NOTE:_** When making those vectors from points, let say $\vec{PQ}$, you should subtract $Q$ from $P$, so subtract the second term from the first

Now that we have a normal vector and a point, we can use the equation

$$a(x - x_0) + b(y - y_0) + c(z - z_0) = 0$$
to get the form 

$$Ax + By + Cz + D = 0$$

where $a, b, c$ are the constant from the vector, and $x_0, y_0, z_0$ are values from a point

## Finding the distance
Now that we know the formula for a place, we can use the formula

$$\text{distance} = \frac{{|Ax_1 + By_1 + Cz_1 + D|}}{{\sqrt{A^2 + B^2 + C^2}}}$$

to find the distance, by plugging in the values

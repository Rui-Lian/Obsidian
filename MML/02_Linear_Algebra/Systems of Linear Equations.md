Background: A factory

n Products: 

$$
N_1, \dots N_n
$$

Need m resourcws: 

 $$
 R_1, \dots R_m
$$


Meaning of Matrix multiplied by a vector

1. Row perspective

#row_view

$$
\begin{bmatrix}
a_{11} & a_{12} & \cdots & a_{1n} \\
a_{21} & a_{22} & \cdots & a_{2n} \\
\dots & \dots & \dots & \dots \\
a_{m1} & a_{m2} & \cdots & a_{mn} 
\end{bmatrix} \times 
\begin{bmatrix}
x_1 \\
x_2 \\
\vdots \\
x_n
\end{bmatrix}
$$


Meaning of the first row in the matrix: 

$$
a_{11}x_1 + a_{12}x_2 + \cdots + a_{1n}x_n = \text{first resource needed in all n product}
$$

Similarly, the meaning of the $i$th row: 

$$
a_{i1}x_1 + a_{i2}x_2 + \cdots + a_{in}x_n = \text{the ith resource needed in all n product}
$$

#Column_view


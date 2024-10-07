## Background: A factory

n Products: 

$$
N_1, \dots N_n
$$

Need m resources: 

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
\end{bmatrix} = 
x_1 
\begin{bmatrix}
a_{11} \\
a_{21} \\
\vdots \\
a_{m1}
\end{bmatrix} + 
x_2
\begin{bmatrix}
a_{12} \\
a_{22} \\
\vdots \\
a_{m2}
\end{bmatrix} + 
\cdots + 
x_n \begin{bmatrix}
a_{1n} \\
a_{2n} \\
\vdots \\
v{mn}
\end{bmatrix} = 
\begin{bmatrix}
b_1 \\ b_2 \\ \vdots \\b_n
\end{bmatrix}
$$

Meaning of column: 
Resources are needed for product $x_i$, . 

$$
\begin{bmatrix}
x_{i1} \\
x_{i2} \\
\vdots \\
x_{in}
\end{bmatrix}
$$

Total resources is: 

$$
\begin{bmatrix}
b_1 \\ b_2 \\ \vdots \\b_n
\end{bmatrix}
$$
Python file with function multiply_matrices that takes as input a list of numpy arrays and outputs their product. Raises custom exceptionif there is a pair of incompatible matrices

$$\begin{bmatrix}
    a  &  b      \\
    c  &  d
\end{bmatrix}
\times
\begin{bmatrix}
    e  &  f  &  g      \\
    h  &  i  &  j
\end{bmatrix}
=
\begin{bmatrix}
    (a \times e) + (b \times h)  &  (a \times f) + (b \times i)  &  (a \times g) + (b \times j)      \\
    (c \times e) + (d \times h)  &  (c \times f) + (d \times i)  &  (c \times g) + (d \times j)      \\
\end{bmatrix}$$

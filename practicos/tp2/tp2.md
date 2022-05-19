# 1
Simplificar las siguientes funciones booleanas a un número mínimo de literales.

## a
> $x . y + x . y^\prime$

$$
\begin{array}{c}
x . y + x . y^\prime &=& x . (y + y^\prime) \\
&=& x.1 \\
&=& x \\
\end{array}
$$

## b
> $(x + y).(x + y^\prime)$

$$
\begin{array}{c}
(x + y).(x + y^\prime) &=& x + (y . y^\prime) \\
&=& x + 0 \\
&=& x \\
\end{array}
$$

## c
> $x . y . z + x^\prime . y + x . y . z^\prime$

$$
\begin{array}{c}
x . y . z + x^\prime . y + x . y . z^\prime &=& x . (y . z + y . z^\prime) + x^\prime . y \\
&=& x . y + x^\prime . y \\
&=& y \\
\end{array}
$$

## d
> $z . x + z . x^\prime . y$

$$
z . x + z . x^\prime . y = z . (x + x^\prime . y)
$$

## e
>$(A + B)^\prime . (A^\prime + B^\prime)^\prime$

$$
\begin{array}{c}
(A + B)^\prime . (A^\prime + B^\prime)^\prime &=& ((A + B) + (A^\prime + B^\prime))^\prime \\
&=& (A + A^\prime + B + B^\prime)^\prime \\
&=& (1 + 1)^\prime \\
&=& 0 \\
\end{array}
$$

## f
> $y . (w . z^\prime + w . z) + x . y$

$$
\begin{array}{c}
y . (w . z^\prime + w . z) + x . y &=& y . (w) + x . y \\
&=& y . (w + x) \\
\end{array}
$$

# 2
Reducir a un número mínimo de literales las siguientes funciones booleanas:

### a
> $(B.C^\prime + A^\prime.D).(A.B^\prime + C.D^\prime)$

$$
\begin{array}{c}
(B.C^\prime + A^\prime.D).(A.B^\prime + C.D^\prime) &=& B.C^\prime.(A.B^\prime + C.D^\prime) + A^\prime.D.(A.B^\prime + C.D^\prime) \\
&=& B.C^\prime.A.B^\prime + B.C^\prime.C.D^\prime + A^\prime.D.A.B^\prime + A^\prime.D.C.D^\prime \\
&=& 0 + 0 + 0 + 0 \\
&=& 0 \\
\end{array}
$$

### b
> $B^\prime.D + A^\prime.B.C^\prime + A.C.D + A^\prime.B.C$

$$
\begin{array}{c}
B^\prime.D + A^\prime.B.C^\prime + A.C.D + A^\prime.B.C \\ \\
D.(B^\prime + A.C) + A^\prime.B.(C^\prime + C) \\ \\
D.B^\prime + A.C.D + A^\prime.B \\ \\
D.B^\prime(C + C^\prime) + A.C.D(B + B^\prime) + A^\prime.B(C + C^\prime) \\ \\
D.B^\prime.C^\prime + D.B^\prime.C + A.C.D.B + A.C.D.B^\prime + A^\prime.B.C(D + D^\prime) + A^\prime.B.C^\prime(D + D^\prime) \\ \\
D.B^\prime.C^\prime(A + A^\prime) + D.B^\prime.C(A + A^\prime) + A.C.D.B + A.C.D.B^\prime + A^\prime.B.C.D + A^\prime.B.C.D^\prime \\ {} + A^\prime.B.C^\prime.D + A^\prime.B.C^\prime.D^\prime \\ \\
D.B^\prime.C^\prime.A + D.B^\prime.C^\prime.A^\prime + D.B^\prime.C.A + D.B^\prime.C.A^\prime \\ {} + A.C.D.B + A.C.D.B^\prime + A^\prime.B.C.D^\prime + A^\prime.B.C^\prime.D + A^\prime.B.C^\prime.D^\prime \\ \\
D.B^\prime.C^\prime.A + D.B^\prime.C^\prime.A^\prime + D.B^\prime.C.A + D.B^\prime.C.A^\prime \\ {} + D.B.C.A + D.B^\prime.C.A + D^\prime.B.C.A^\prime + D.B.C^\prime.A^\prime + D^\prime.B.C^\prime.A^\prime \\ \\
(D.B^\prime.C^\prime.A + D.B^\prime.C^\prime.A^\prime + D.B^\prime.C.A + D.B^\prime.C.A^\prime) \\ {} + (D.B.C.A + D.B^\prime.C.A) + (D^\prime.B.C.A^\prime + D.B.C^\prime.A^\prime + D^\prime.B.C^\prime.A^\prime) \\ \\
(D.B^\prime.C^\prime.A + D.B^\prime.C^\prime.A^\prime + D.B^\prime.C.A + D.B^\prime.C.A^\prime) \\ {} + (D.B.C.A + (D.B^\prime.C.A + D^\prime.B.C.A^\prime + D.B.C^\prime.A^\prime + D^\prime.B.C^\prime.A^\prime) \\ \\
\end{array}
$$

### c
> $[(A.B)’.A].[(A.B)’.B]$



### d
> A.B’ + C’.D’
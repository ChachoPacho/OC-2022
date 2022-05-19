### Ejercicio 1:
Convertir los siguientes números en hexadecimal a binario de 32 bits:

#### a
- 0xABCDEF00

__1010 1011 1100 1101 1110 1111 0000 0000__

#### b
- 0x123456

_0000 0000_ __0001 0010 0011 0100 0101 0110__

#### c
- 0x8E3FC581

__1000 1110 0011 1111 1100 0101 1000 0001__

#### d
- 0x10A6F2B

_0000_ __0001 0000 1010 0110 1111 0010 1011__

### Ejercicio 2:
Convertir los siguientes números en binario a decimal y a hexadecimal:

| Binario                              | Hexadecimal | Decimal           |
| ------------------------------------ | ----------- | ----------------- |
| $(1110011110000011)_2$               | 0xE783      | 59267             |
| $(10110111001101000101111)_2$        | 0x5B9A2F    | 6003247           |
| $(10110011011011.11000010000)_2$     | 0x2CDB.C20  | 11483.7578125     |
| $(10001111110100011111.000001101)_2$ | 0x8FD1F.068 | 589087.0253960625 |

- 1110 0111 1000 0011 = E 7 8 3
$$
\begin{array}{l}
=& 1 + 2 + 2^7 + 2^8 + 2^9 + 2^{10} + 2^{13} + 2^{14} + 2^{15} \\
=& 59267
\end{array}
$$

- 101 1011 1001 1010 0010 1111 = 5 B 9 A 2 F
$$
\begin{array}{l}
=& 1 + 2 + 4 + 8 + 32 + 2^9 + 2^{11} + 2^{12} + 2^{15} + 2^{16} + 2^{17} + 2^{19} + 2^{20} + 2^{22} \\
=& 6003247
\end{array}
$$

- 10 1100 1101 1011.1100 0010 000 = 2 C D B . C 2 0
$$
\begin{array}{l}
=& 2^{-7} + 2^{-2} + 2^{-1} + 1 + 2 + 8 + 16 + 64 + 128 + 2^{10} + 2^{11} + 2^{13} \\
=& 11483.7578125
\end{array}
$$

- 1000 1111 1101 0001 1111 . 0000 0110 1 = 8 F D 1 F . 0 6 8
$$
\begin{array}{l}
=& 2^{-9} + 2^{-7} + 2^{-6} + 1 + 2 + 4 + 8 + 16 + 2^{8} + 2^{10} + 2^{11} + 2^{12} + 2^{13} + 2^{14} + 2^{15} + 2^{19} \\
=& 589087.0253960625
\end{array}
$$

### Ejercicio 3:
Suponiendo que se tienen registros de 16 bits, convertir a binario sin signo los siguientes números en base 10:

#### a
- $123_{10}$

$$
\begin{array}{l}
123 &=& 128 - 5 \\
&=& 2^7 - (2^2 + 2^0) \\
&=& 1000 0000 - 101 \\
&=& 0111 1011
\end{array}
$$

__0000 0000 0111 1011__

#### b
- $59_{10}$

$$
\begin{array}{l}
59 &=& 123 - 64 \\
&=& 111 1011 - 100 0000 \\
&=& 011 1011
\end{array}
$$

__0000 0000 0011 1011__

#### c
- $255.46_{10}$

$$
\begin{array}{l}
255.46 &=& 255 + 0.46 \\
&=& 2^7 + 2^6 + 2^5 + 2^4 + 2^3 + 2^2 + 2 + 1 + 0.46 \\
&=& 1111 1111 \\
\end{array}
$$

__0000 0000 1111 1111__

#### d
- $98.019_{10}$

$$
\begin{array}{l}
98.019 &=& 98 + 0.19 \\
&=& 64 + 32 + 2 \\
&=& 2^6 + 2^5 + 2 \\
&=& 110 0010 \\
\end{array}
$$

__0000 0000 0110 0010__

### Ejercicio 4:
Suponiendo que un microprocesador utiliza registros de 8 bits y representación de números negativos en complemento a 2, muestre el contenido de estos registros al codificar en binario los siguientes números con signo:

#### a
- $-76_{10}$

$$
\begin{array}{l}
76 &=& 64 + 8 + 4 \\
&=& 2^6 + 2^3 + 2^2 \\
&=& 100 0000 + 1000 + 100 \\
&=& 100 1100 \\
\\
-76 &=& 1000 0000 - 0100 1100 \\
&=& 1011 0100
\end{array}
$$

__1011 0100__

#### b
- $-43_{10}$

$$
\begin{array}{l}
43 &=& 32 + 8 + 2 + 1 \\
&=& 2^5 + 2^3 + 2^1 + 2^0 \\
&=& 0010 1011 \\
\\
-43 &=& 1000 0000 - 0010 1011 \\
&=& 1101 0101
\end{array}
$$

__1101 0101__

#### c
- $64_{10}$

$$
\begin{array}{l}
64 &=& 2^6 \\
&=& 0100 0000 \\
\end{array}
$$

__0100 0000__

#### d
- $-121_{10}$

$$
\begin{array}{l}
121 &=& 64 + 32 + 16 + 8 + 1 \\
&=& 2^6 + 2^5 + 2^4 + 2^3 + 2^0 \\
&=& 0111 1001 \\
\\
-121 &=& 1000 0000 - 0111 1001 \\
&=& 1000 0111
\end{array}
$$

__1000 0111__

### Ejercicio 5:
Convertir los siguientes valores binarios de 8 bits en formato de complemento a dos a decimal:

#### a
- 1001 0110
- Negativo

$$
\begin{array}{l}
1000 0000 - 1001 0110 &=& 0110 1010 \\
\\
0110 1010 &=& 2^6 + 2^5 + 2^3 + 2 \\
&=& 64 + 32 + 8 + 2 \\
&=& 106
\end{array}
$$

__-106__

#### b
- 1111 1011
- Negativo

$$
\begin{array}{l}
1000 0000 - 1111 1011 &=& 0000 0101 \\
\\
0000 0101 &=& 2^2 + 1 \\
&=& 5 \\
\end{array}
$$

__-5__

#### c
- 1110 0000
- Negativo

$$
\begin{array}{l}
1000 0000 - 1110 0000 &=& 0010 0000 \\
\\
0010 0000 &=& 2^5 \\
&=& 32 \\
\end{array}
$$

__-32__

#### d
- 0001 1110
- Positivo

$$
\begin{array}{l}
0001 1110 &=& 2^4 + 2^3 + 2^2 + 2 \\
&=& 16 + 8 + 4 + 2 \\
&=& 30 \\
\end{array}
$$

__30__

### Ejercicio 6:
Suponga que los registros A y B del microprocesador del ejercicio 4 (registros de 8 bits) contienen los valores 0x80 y 0xD0 respectivamente.

- $A = 0x80 = 0100 0000 = 64$
- $B = 0xD0 = 1101 0000 = -(0011 0000) = -48$

#### a
- ¿Qué valor contiene el registro C después de ejecutar la operación C = A + B? __0001 0000__ (El resultado es de 9 bits, pero no hay _overflow_, por lo que se toman los últimos 8 bits).
- ¿El resultado que se guarda en C es el esperado? Sí.

$$
\begin{array}{l}
C &=& 0100 0000 + 1101 0000 \\
&=& 1 0001 0000 \\
&=& 0001 0000 \\
&=& 16 \\
\\
&=& 64 + (-48) \\
&=& 16 \\
\end{array}
$$

#### b
- ¿Qué valor contiene el registro C después de ejecutar la operación C = A - B? __0111 0000__ 
- ¿El resultado que se guarda en C es el esperado? Sí.

$$
\begin{array}{l}
C &=& 0100 0000 - 1101 0000 \\
&=& 0100 0000 + 0011 0000 \\
&=& 0111 0000 \\
&=& 112 \\
\\
&=& 64 - (-48) \\
&=& 112 \\
\end{array}
$$

#### c
En base al análisis de las operaciones anteriores, ¿cuál es la ventaja de la representación de números negativos mediante su complemento a 2, por sobre la representación binaria regular + un bit de signo?

### Ejercicio 7:
Expresar los siguientes números decimales en su representación binaria (negativos en complemento a 2) considerando los tamaños de los registros donde serán alojados según la tabla.

| Decimal |           | Binario             |                                         |
| ------- | :---------: | :-------------------: | :---------------------------------------: |
|         | Byte      | HalfWord            | Word                                    |
| 113     | 0111 0001 | 0000 0000 0111 0001 | 0000 0000 0000 0000 0000 0000 0111 0001 |
| -63     | 1100 0001 | 1111 1111 1100 0001 | 1111 1111 1111 1111 1111 1111 1100 0001 |
| 319     | ---- ---- | 0000 0001 0011  1111 | 0000 0000 0000 0000 0000 0001 0011  1111 |
| -128    | 1000 0000 | 1111 1111 1000 0000 | 1111 1111 1111 1111 1111 1111 1000 0000 |
| 65535   | ---- ---- | 0111 1111 1111 1111 | 0000 0000 0000 0000 0111 1111 1111 1111 |
| -149744 | ---- ---- | ---- ---- ---- ---- | 1111 1111 1111 1101 1011 0111 0001 0000 |

### Ejercicio 8:
Convertir los siguientes números decimales a formato IEEE 754 de precisión simple (normalizados):

#### a
- $5678_{10}$

$$
\begin{array}{l}
5678 &=& 4096 + 1024 + 512 + 32 + 8 + 4 + 2 \\
&=& 2^{12} + 2^{10} + 2^9 + 2^5 + 2^3 + 2^2 + 2 \\
&=& 1 0110 0010 1110 \\
\\

Fraction &=& 1 . 0110 0010 1110 \\
Exponent + Bias &=& 12 + 127 = 139 \\
S &=& 0 \\
\\

139 &=& 128 + 8 + 2 + 1 \\
&=& 2^7 + 2^3 + 2 + 2^0 \\
&=& 1000 1011 \\
\end{array}
$$

__0 - 1000 1011 - 0110 0010 1110 0000 0000 000 __

#### b
- $306.59375_{10}$

$$
\begin{array}{l}
306.59375 &=& 256 + 32 + 16 + 2 + 0.5 + 0.0625 + 0.03125 \\
&=& 2^8 + 2^5 + 2^4 + 2 + 2^{-1} + 2^{-4} + 2^{-5} \\
&=& 1 0011 0010 . 1001 1 \\
\\

Fraction &=& 1 . 0011 0010 1001 1 \\
Exponent + Bias &=& 8 + 127 = 135 \\
S &=& 0 \\
\\

135 &=& 128 + 4 + 2 + 1 \\
&=& 2^7 + 2^2 + 2 + 2^0 \\
&=& 1000 0111 \\
\end{array}
$$

__0 - 1000 0111 - 0011 0010 1001 1000 0000 000__



#### c
- $723.125_{10}$

$$
\begin{array}{l}
723.125 &=& 512 + 128 + 64 + 16 + 2 + 1 + 0.125 \\
&=& 2^9 + 2^7 + 2^6 + 2^4 + 2 + 2^0 + 2^{-3} \\
&=& 10 1101 0011 . 001 \\
\\

Fraction &=& 1 . 0110 1001 1001 \\
Exponent + Bias &=& 9 + 127 = 136 \\
S &=& 0 \\
\\

136 &=& 128 + 8 \\
&=& 2^7 + 2^3 \\
&=& 1000 1000 \\
\end{array}
$$

__0 - 1000 1000 - 0110 1001 1001 0000 0000 000__



#### d
- $18.1953125_{10}$

$$
\begin{array}{l}
18.1953125 &=& 16 + 2 + 0.125 + 0.0625 + 0.0078125 \\
&=& 2^4 + 2 + 2^{-3} + 2^{-4} + 2^{-7}\\
&=& 1 0010 . 0011 001 \\
\\

Fraction &=& 1 . 0010 0011 001 \\
Exponent + Bias &=& 4 + 127 = 131 \\
S &=& 0 \\
\\

131 &=& 128 + 3 \\
&=& 2^7 + 2 + 1 \\
&=& 1000 0011 \\
\end{array}
$$

__0 - 1000 0011 - 0010 0011 0010 0000 0000 000__



#### e
- $-3020.993_{10}$

$$
\begin{array}{l}
3020.993 &=& 2048 + 512 + 256 + 128 + 64 + 8 + 4 + + 0.5 + 0.25 + 0.125 + 0.0625 + {} \\
&& 0.03125 + 0.015625 + 0.0078125 + 0.00048828125 + 0.000244140625 + {...} \\
&=& 2^{11} + 2^9 + 2^8 + 2^7 + 2^6 + 2^3 + 2^2 + 2^{-1} + 2^{-2} + 2^{-3} + 2^{-4} + 2^{-5} + 2^{-6} + 2^{-7} + 2^{-11} + 2^{-12} \\
&=& 1011 1100 1100 . 1111 1110 0011 \\
\\

Fraction &=& 1 . 011 1100 1100 1111 1110 0011 \\
Exponent + Bias &=& 11 + 127 = 138 \\
S &=& 1 \\
\\

138 &=& 128 + 8 + 2 \\
&=& 2^7 + 8 + 2 \\
&=& 1000 1010 \\
\end{array}
$$

__1 - 1000 1010 - 0111 1001 1001 1111 1100 011__



#### f
- $-0.000892_{10}$

$$
\begin{array}{l}
0.000892 &=& 0.00048828125 + 0.000244140625 + + 0.0001220703125 + {...} \\
&=& 2^{-11} + 2^{-12} + 2^{-13} \\
&=& 0 . 0000 0000 0011 1010 0111 0101 0100 0110 11010\\
\\

Fraction &=& 1 . 1101 0011 1010 1010 0011 011\\
Exponent + Bias &=& -11 + 127 = 116 \\
S &=& 1 \\
\\

116 &=& 64 + 32 + 16 + 4 \\
&=& 2^6 + 2^5 + 2^4 + 2^2 \\
&=& 0111 0100 \\
\end{array}
$$

__1 - 0111 0100 - 1101 0011 1010 1010 0011 011__

### Ejercicio 9:
Convertir los siguientes en formato IEEE 754 de precisión simple (normalizados) a números decimales:

#### a
- 1 - 1000 1011 - 0000 0000 0000 1100 0000 000

$$
\begin{array}{l}
1000 1011 &=& 2^7 + 2^3 + 2 + 1 \\ 
&=& 139 \\
\\
Fraction &=& 1.0000 0000 0000 11 \\
S &=& 1 \\
Exponent &=& 139 - 127 &=& 12 \\ 
\\
BinNumber &=& 1 0000 0000 0000. 11 \\
\\
Number &=& (-1)^1 * ( 2^{12} + 2^{-1} + 2^{-2} ) \\
&=& -1 * ( 4096 + 0.5 + 0.25 ) \\
&=& -4096.75
\end{array}
$$

#### b
- 0 - 1000 1001 - 0000 0001 0000 0100 1100 000

$$
\begin{array}{l}
1000 1001 &=& 2^7 + 2^3 + 1 \\ 
&=& 137 \\
\\
Fraction &=& 1.0000 0001 0000 0100 11 \\
S &=& 0 \\
Exponent &=& 137 - 127 &=& 10 \\ 
\\
BinNumber &=& 100 0000 0100. 0001 0011 \\
\\
Number &=& (-1)^0 * ( 2^{10} + 2^2 + 2^{-4} + 2^{-7} + 2^{-8} ) \\
&=& 1024 + 4 + 0.0625 + 0.0078125 + 0.00390625 \\
&=& 1028.07421875
\end{array}
$$

#### c
- 0 -  1000 0100 - 1010 0000 0000 0000 0000 000

$$
\begin{array}{l}
1000 0100 &=& 2^7 + 2^2 \\ 
&=& 132 \\
\\
Fraction &=& 1.101 \\
S &=& 0 \\
Exponent &=& 132 - 127 &=& 5 \\ 
\\
BinNumber &=& 11 0100 \\
\\
Number &=& (-1)^0 * ( 2^5 + 2^4 + 2^2 ) \\
&=& 32 + 16 + 4 \\
&=& 52
\end{array}
$$

#### d
- 0 -  0111 0010 - 0100 1101 0111 0010 0111 101

$$
\begin{array}{l}
0111 0010 &=& 2^6 + 2^5 + 2^4 + 2 \\ 
&=& 114 \\
\\
Fraction &=& 1.0100 1101 0111 0010 0111 101 \\
S &=& 0 \\
Exponent &=& 114 - 127 &=& -13 \\ 
\\
BinNumber &=& 0.0000 0000 0000 1010 0110 1011 1001 0011 1101 \\
\\
Number &=& (-1)^0 * ( 2^{-13} + 2^{-15} + 2^{-18} + 2^{-19} + 2^{-21} + 2^{-23} + {}  \\
&& 2^{-24} + 2^{-25} + 2^{-28} + 2^{-31} + 2^{-32} + 2^{-33} + 2^{-34} + 2^{-36} ) \\
&=& 0.00019592969329096 \\
\end{array}
$$

#### e
- 1 - 0111 0101 - 0110 1100 0110 0001 0101 001 

$$
\begin{array}{l}
0111 0101 &=& 2^6 + 2^5 + 2^4 + 2^2 + 1 \\ 
&=& 117 \\
\\
Fraction &=& 1.0110 1100 0110 0001 0101 001  \\
S &=& 1 \\
Exponent &=& 117 - 127 &=& -10 \\ 
\\
BinNumber &=& 0.0000 0000 0101 1011 0001 1000 0101 0100 1  \\
\\
Number &=& (-1)^0 * ( 2^{-10} + 2^{-12} + 2^{-13} + 2^{-15} + 2^{-16} + 2^{-20} + {}  \\
&& 2^{-21} + 2^{-26} + 2^{-28} + 2^{-30} + 2^{-33} ) \\
&=& -0.0013885498046875 \\
\end{array}
$$

#### f
- 1 - 1111 1111 - 0000 0000 0000 0000 0000 000 

$$
-\infty
$$

### Ejercicio 10:
Investigar cómo se escriben los símbolos especiales (“NaN”, “+Infinito”, “Infinito”, “+0”, “0”) en formato IEEE 754 de precisión simple (normalizados).
$$
\begin{array}{l}
NaN &=& 1 - 1111 1111 - 0000 0000 0000 0000 0000 001  \\
+\infty &=& 0 - 1111 1111 - 0000 0000 0000 0000 0000 000 \\
-\infty &=& 1 - 1111 1111 - 0000 0000 0000 0000 0000 000 \\
+0 &=& 0 - 0000 0000 - 0000 0000 0000 0000 0000 000 \\
-0 &=& 1 - 0000 0000 - 0000 0000 0000 0000 0000 000 \\
\end{array}
$$


### Ejercicio 11:
Existe una representación denominada IEEE 754 de media precisión que sólo ocupa 16 bits de la siguiente forma: 1 para signo, 5 para exponente (con base +15) y 10 para mantisa. Tomar los tres números del ejercicio 8 y transformarlos a media precisión. ¡Cuidado! Puede que alguno no entre o haya que redondear. En cualquier caso escribir la diferencia entre el número obtenido en media precisión y el original en simple precisión.

#### a
- $5678_{10}$

$$
\begin{array}{l}
5678 &=& 4096 + 1024 + 512 + 32 + 8 + 4 + 2 \\
&=& 2^{12} + 2^{10} + 2^9 + 2^5 + 2^3 + 2^2 + 2 \\
&=& 1 0110 0010 1110 \\
\\

Fraction &=& 1 . 0110 0010 1110 \\
Exponent + Bias &=& 12 + 15 = 27 \\
S &=& 0 \\
\\

27 &=& 16 + 8 + 2 + 1 \\
&=& 2^4 + 2^3 + 2 + 2^0 \\
&=& 1 1011 \\
\end{array}
$$

__0 - 1 1011 - 0110 0010 11__

- Diferencia de: __0 - 1000 1011 - 0000 0000 0010 0000 0000 000__

#### b
- $306.59375_{10}$

$$
\begin{array}{l}
306.59375 &=& 256 + 32 + 16 + 2 + 0.5 + 0.0625 + 0.03125 \\
&=& 2^8 + 2^5 + 2^4 + 2 + 2^{-1} + 2^{-4} + 2^{-5} \\
&=& 1 0011 0010 . 1001 1 \\
\\

Fraction &=& 1 . 0011 0010 1001 1 \\
Exponent + Bias &=& 8 + 15 = 23 \\
S &=& 0 \\
\\

23 &=& 16 + 4 + 2 + 1 \\
&=& 2^4 + 2^2 + 2 + 2^0 \\
&=& 1 0111 \\
\end{array}
$$

__0 - 1 0111 - 0011 0010 10__

- Diferencia de: __0 - 1000 0111 - 0000 0000 0001 1000 0000 000__

#### c
- $723.125_{10}$

$$
\begin{array}{l}
723.125 &=& 512 + 128 + 64 + 16 + 2 + 1 + 0.125 \\
&=& 2^9 + 2^7 + 2^6 + 2^4 + 2 + 2^0 + 2^{-3} \\
&=& 10 1101 0011 . 001 \\
\\

Fraction &=& 1 . 0110 1001 1001 \\
Exponent + Bias &=& 9 + 15 = 24 \\
S &=& 0 \\
\\

24 &=& 16 + 8 \\
&=& 2^4 + 2^3 \\
&=& 1 1000 \\
\end{array}
$$

__0 - 1 1000 - 0110 1001 10__

- Diferencia de: __0 - 1000 1000 - 0000 0000 0001 0000 0000 000__

#### d
- $18.1953125_{10}$

$$
\begin{array}{l}
18.1953125 &=& 16 + 2 + 0.125 + 0.0625 + 0.0078125 \\
&=& 2^4 + 2 + 2^{-3} + 2^{-4} + 2^{-7}\\
&=& 1 0010 . 0011 001 \\
\\

Fraction &=& 1 . 0010 0011 001 \\
Exponent + Bias &=& 4 + 15 = 19 \\
S &=& 0 \\
\\

19 &=& 16 + 3 \\
&=& 2^4 + 2 + 1 \\
&=& 1 0011 \\
\end{array}
$$

__0 - 1 0011 - 0010 0011 00__

- Diferencia de: __0 - 1000 0011 - 0000 0000 0010 0000 0000 000__

#### e
- $-3020.993_{10}$

$$
\begin{array}{l}
3020.993 &=& 2048 + 512 + 256 + 128 + 64 + 8 + 4 + + 0.5 + 0.25 + 0.125 + 0.0625 + {} \\
&& 0.03125 + 0.015625 + 0.0078125 + 0.00048828125 + 0.000244140625 + {...} \\
&=& 2^{11} + 2^9 + 2^8 + 2^7 + 2^6 + 2^3 + 2^2 + 2^{-1} + 2^{-2} + 2^{-3} + 2^{-4} + 2^{-5} + 2^{-6} + 2^{-7} + 2^{-11} + 2^{-12} \\
&=& 1011 1100 1100 . 1111 1110 0011 \\
\\

Fraction &=& 1 . 011 1100 1100 1111 1110 0011 \\
Exponent + Bias &=& 11 + 15 = 26 \\
S &=& 1 \\
\\

26 &=& 16 + 8 + 2 \\
&=& 2^4 + 8 + 2 \\
&=& 1 1010 \\
\end{array}
$$

__1 - 1 1010 - 0111 1001 10__

- Diferencia de: __1 - 1000 1010 - 0000 0000 0001 1111 1100 011__

#### f
- $-0.000892_{10}$

$$
\begin{array}{l}
0.000892 &=& 0.00048828125 + 0.000244140625 + + 0.0001220703125 + {...} \\
&=& 2^{-11} + 2^{-12} + 2^{-13} \\
&=& 0 . 0000 0000 0011 1010 0111 0101 0100 0110 11010\\
\\

Fraction &=& 1 . 1101 0011 1010 1010 0011 011\\
Exponent + Bias &=& -11 + 15 = 4 \\
S &=& 1 \\
\\

4 &=& 2^2 \\
&=& 0 0100 \\
\end{array}
$$

__1 - 0 0100 - 1101 0011 10__

- Diferencia de: __1 - 0 0100 - 0000 0000 0010 1010 0011 011__

### Ejercicio 12
Dar una secuencia de 3 números binarios de 32 bits que sea significativa tanto al interpretarlos como números binarios sin signo como números IEEE 754 de precisión simple. ¿Existe algún número binario de 32 bits que interpretado como binario sin signo sea igual a la interpretación IEEE 754 de simple precisión?

- Tiene que ser positivo $\to$ primer bit = 0.
- No puede ser fraccionario $\to$ E $\ge 127$ 
- El máximo valor que van a poder los de IEEE 754 es el máximo valor de los sin signo $4.294.967.295$
- Si elegimos un número que ocupe $25 bits$, como el mantra agarra hasta $24$, vamos a tener espejos cada $1$ número, es decir, todos los números pares van a tener la misma representación que su siguiente número impar. Pero si nos vamos a $26 bits$, estos espejos se van a mantener cada $4$ números y así sucesivamente.
- Número acotado entre:
$$
\begin{array}{l}
Max &=& 0 - 1001 1110 - 1111 1111 1111 1111 1111 111 \\
Min &=& 0 - 1001 0111 - 0000 0000 0000 0000 0000 000 \\
\end{array}
$$

	- De sin signo a decimal son
$$
\begin{array}{l}
Max &=& 1.333.788.671 \\
Min &=& 1.266.679.808 \\
\end{array}
$$

	- De IEEE a decimal son
$$
\begin{array}{l}
Max &=& 4.294.967.295 \\
Min &=& 16.777.216 \\
\end{array}
$$

- Como los rangos son muy amplios, los acortamos:
$$
\begin{array}{l}
Max &=& 0 - 1001 1101 - 0011 1101 1111 1111 1111 111 \\
Min &=& 0 - 1001 1101 - 0010 1110 0000 0000 0000 000 \\
\end{array}
$$

	- Sin signo
$$
\begin{array}{l}
Max &=& 1.319.043.071 \\
Min &=& 1.318.518.784 \\
\end{array}
$$

- Volvemos a acortarlos:
$$
\begin{array}{l}
Max &=& 0 - 1001 1101 - 0011 1010 0111 1011 1111 111 \\
Min &=& 0 - 1001 1101 - 0011 1010 0101 1100 0000 000 \\
\end{array}
$$

	- Sin signo
$$
\begin{array}{l}
Max &=& 1.318.927.871 \\
Min &=& 1.318.923.776 \\
\end{array}
$$

- Como ambos mínimos se representan en $31 bits$
$$
\begin{array}{c}
31 - 24 &=& 7 \\
2^7 &=& 128 \\
\end{array}
$$

	Es decir, tenemos espejos durante $128$ números decimales.
- Calculamos la diferencia entre los mínimos
$$
1318923776 - 1318518784 = 404992
$$

Luego, sabemos que $IEEE$ avanza $1$ por cada $128$ en decimal, pero _sin signo_ avanza 1 por cada 1 en decimal.
$$
\begin{array}{c}
404992 \div 128 &=& 3164 \\
3164 \div 128 &=& 24.71875 \\
\\
404992 + 3164 + 24 &=& 408180 \\
408180 + 1318518784 &=& 1318926964
\end{array}
$$

En $1.318.926.964$ estaríamos muy cerca de _sin signo_, de hecho
$$

\begin{array}{c}
IEEE &=& 0 - 1001 1101 - 0011 1010 0111 0100 1110 100 \\
SS &=& 0 - 1001 1101 - 0011 1010 0111 0100 1110 100 \\
\end{array}
$$

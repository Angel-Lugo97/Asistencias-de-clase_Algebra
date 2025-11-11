# Tecnológico de Software
## Materia: Fundamentos de álgebra
## Alumno: Angel Abraham Lugo Saenz
## Grupo: B
## Actividad #16.  Matrices documentación


# Objetivo

El objetivo es comprender los diferentes tipos de matrices y dominar las operaciones básicas como suma, resta, multiplicación y transposición, para aplicar estos conceptos en la resolución de problemas algebraicos y en la manipulación de sistemas lineales. Además, se busca verificar propiedades clave, como la asociativa de la multiplicación de matrices.

---
### Muestra  

*Calcula la suma de A y B*

$$
A =
\begin{pmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
\end{pmatrix}
$$

$$
B =
\begin{pmatrix}
9 & 10 & 11 \\
12 & 13 & 14 \\
\end{pmatrix}
$$

*Desarrollo:*

$$
A + B =
\begin{pmatrix}
1 + 9 & 2 + 10 & 3 + 11 \\
4 + 12 & 5 + 13 & 6 + 14 \\
\end{pmatrix}
$$

*Resultado final:*

$$
A + B =
\begin{pmatrix}
10 & 12 & 14 \\
16 & 18 & 20 \\
\end{pmatrix}
$$

## Índice
- [Ejercicio 1: Clasificación de matrices](#ejercicio-1-clasificación-de-matrices)
- [Ejercicio 2: Operaciones con matrices](#ejercicio-2-operaciones-con-matrices)
- [Ejercicio 3: Multiplicación cadena](#ejercicio-3-multiplicación-cadena)

---

# Ejercicio 1: Clasificación de matrices

## Objetivo del ejercicio: 

El objetivo es aprender a identificar y clasificar las matrices según sus propiedades, como ser cuadradas, diagonales, simétricas o triangulares, y aplicar estos conocimientos en la resolución de problemas algebraicos y en el análisis de sistemas lineales.

### a) 

$$A = \begin{bmatrix}
1 & 0 \\
0 & 1 
\end{bmatrix}$$

Es una matriz  **identidad**  porque tiene **unos** en su diagonal principal y **ceros** en todas las demás posiciones.

### b) 

$$ B = \begin{bmatrix}
3 & 0 & 0 \\
0 & -2 & 0 \\
0 & 0 & 5 
\end{bmatrix}  $$

Es una matriz  **diagonal** porque **todos sus elementos son ceros**, **salvo en la diagonal principal**.

### c)

$$C = \begin{bmatrix}
2 & 1 & 4 \\
1 & 3 & 5 \\
4 & 5 & 6 
\end{bmatrix}  $$

Es una matriz **simétrica** porque se cumple que **$a_{ij} = a_{ji}$**,  lo que indica que es simétrica con respecto a su diagonal principal.

### d)

$$ D = \begin{bmatrix}
1 & 2 & 3 \\
0 & 4 & 5 \\
0 & 0 & 6 
\end{bmatrix}  $$

Es una matriz  **triangular superior** porque  **todos los elementos situados por debajo de la diagonal principal son ceros**.

---

# Ejercicio 2: Operaciones con matrices

## Objetivo del ejercicio:

El objetivo es dominar las operaciones elementales con matrices, como la suma, resta, multiplicación y transposición, para poder manipular y resolver problemas de matrices de manera efectiva y comprender su funcionamiento básico en diversos contextos matemáticos.

Dadas las matrices:

$$ A = \begin{bmatrix}
2 & -1 \\
3 & 4 
\end{bmatrix}, \quad B = \begin{bmatrix}
5 & 2 \\
-1 & 3 
\end{bmatrix} $$

Calcula: 

### a) Suma de matrices: \( A + B \)
$$ A + B = \begin{bmatrix}
2 + 5 & -1 + 2 \\
3 + (-1) & 4 + 3
\end{bmatrix} = \begin{bmatrix}
7 & 1 \\
2 & 7
\end{bmatrix} $$

### b) Resta y multiplicación de matrices: \(2A - B \)

$$ 2A - B = 2 \begin{bmatrix}
2 & -1 \\
3 & 4
\end{bmatrix} - \begin{bmatrix}
5 & 2 \\
-1 & 3
\end{bmatrix} = \begin{bmatrix}
4 & -2 \\
6 & 8
\end{bmatrix} - \begin{bmatrix}
5 & 2 \\
-1 & 3
\end{bmatrix} = \begin{bmatrix}
-1 & -4 \\
7 & 5
\end{bmatrix} $$

### c) Multiplicación de matrices: \( AB \)
$$ AB = \begin{bmatrix}
2 & -1 \\
3 & 4
\end{bmatrix} \begin{bmatrix}
5 & 2 \\
-1 & 3
\end{bmatrix} = \begin{bmatrix}
2\cdot5+(-1)\cdot(-1) & 2\cdot2+(-1)\cdot3\\
3\cdot5+4\cdot(-1)    & 3\cdot2+4\cdot3
\end{bmatrix} = \begin{bmatrix}
11 & 1 \\
11 & 18
\end{bmatrix} $$

### d) Multiplicación de matrices: \( BA \)
$$ BA = \begin{bmatrix}
5 & 2 \\
-1 & 3
\end{bmatrix} \begin{bmatrix}
2 & -1 \\
3 & 4
\end{bmatrix} = \begin{bmatrix}
(5\cdot2) + (2\cdot3) & (5\cdot-1) + (2\cdot4) \\
(-1\cdot2) + (3\cdot3) & (-1\cdot-1) + (3\cdot4)
\end{bmatrix} = \begin{bmatrix}
16 & 3 \\
7 & 13
\end{bmatrix} $$

### e) Transpuesta de la matriz A: \( A^T \)
$$ A^T = \begin{bmatrix}
2 & 3 \\
-1 & 4
\end{bmatrix} $$

---

# Ejercicio 3: Multiplicación cadena

## Objetivo del ejercicio:
El objetivo es comprobar la propiedad asociativa de la multiplicación de matrices mediante el cálculo de productos sucesivos, asegurando que el orden de las operaciones no afecta el resultado. Esto permite entender mejor cómo interactúan las matrices en operaciones compuestas y fortalecer los fundamentos del álgebra lineal.

---

*Verificar que* $(AB)C = A(BC)$ 

Dadas las matrices:

$$ A = \begin{bmatrix}
1 & 2 \\
3 & 4 
\end{bmatrix}, \quad B = \begin{bmatrix}
2 & 0 \\
1 & 3 
\end{bmatrix}, \quad C = \begin{bmatrix}
1 & 1 \\
0 & 2
\end{bmatrix} $$

### a) Calcular \( (AB)C \)
$$ AB = \begin{bmatrix}
1 & 2 \\
3 & 4
\end{bmatrix} \begin{bmatrix}
2 & 0 \\
1 & 3
\end{bmatrix} = \begin{bmatrix}
(1\cdot2) + (2\cdot1) & (1\cdot0) + (2\cdot3) \\
(3\cdot2) + (4\cdot1) & (3\cdot0) + (4\cdot3)
\end{bmatrix} = \begin{bmatrix}
4 & 6 \\
10 & 12
\end{bmatrix} $$

$$ (AB)C = \begin{bmatrix}
4 & 6 \\
10 & 12
\end{bmatrix} \begin{bmatrix}
1 & 1 \\
0 & 2
\end{bmatrix} = \begin{bmatrix}
(4\cdot1) + (6\cdot0) & (4\cdot1) + (6\cdot2) \\
(10\cdot1) + (12\cdot0) & (10\cdot1) + (12\cdot2)
\end{bmatrix} = \begin{bmatrix}
4 & 16 \\
10 & 34
\end{bmatrix} $$

### b) Calcular \( A(BC) \)
$$ BC = \begin{bmatrix}
2 & 0 \\
1 & 3
\end{bmatrix} \begin{bmatrix}
1 & 1 \\
0 & 2
\end{bmatrix} = \begin{bmatrix}
(2\cdot1) + (0\cdot0) & (2\cdot1) + (0\cdot2) \\
(1\cdot1) + (3\cdot0) & (1\cdot1) + (3\cdot2)
\end{bmatrix} = \begin{bmatrix}
2 & 2 \\
1 & 7
\end{bmatrix} $$

$$ A(BC) = \begin{bmatrix}
1 & 2 \\
3 & 4
\end{bmatrix} \begin{bmatrix}
2 & 2 \\
1 & 7
\end{bmatrix} = \begin{bmatrix}
(1\cdot2) + (2\cdot1) & (1\cdot2) + (2\cdot7) \\
(3\cdot2) + (4\cdot1) & (3\cdot2) + (4\cdot7)
\end{bmatrix} = \begin{bmatrix}
4 & 16 \\
10 & 34
\end{bmatrix} $$

**Conclusión:** la propiedad asociativa de la multiplicación de matrices garantiza que el resultado de la multiplicación no depende de cómo agrupemos las matrices, esto quiere decir, podemos agrupar las matrices de diferentes maneras, como en **$(AB)C = A(BC)$**, y siempre obtendremos el mismo resultado, siempre que las dimensiones sean adecuadas. Esta propiedad es fundamental para realizar cálculos más complejos de manera flexible y eficiente en álgebra lineal.


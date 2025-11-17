# Tecnológico de Software
## Materia: Fundamentos de Álgebra
## Alumno: Angel Abraham Lugo Saenz
## Grupo: B
## Actividad #16.  Matrices documentación

# Objetivo

El objetivo es comprender los determinantes y su importancia en la resolución de sistemas de ecuaciones, aprender técnicas como el método de Sarrus para matrices 3x3 y el cálculo de cofactores para matrices de mayor dimensión. A través de estos conceptos se busca desarrollar habilidades para analizar y resolver problemas algebraicos, como la invertibilidad y la orientación de matrices.

---

### Muestra  

*Calcula la suma de A y B*

$$
A=
\begin{pmatrix}
1 & 2 & 3 \\
4 & 5 & 6
\end{pmatrix}
$$

$$
B=
\begin{pmatrix}
9 & 10 & 11 \\
12 & 13 & 14
\end{pmatrix}
$$

*Desarrollo:*

$$
A+B=
\begin{pmatrix}
1+9 & 2+10 & 3+11 \\
4+12 & 5+13 & 6+14
\end{pmatrix}
$$

*Resultado final:*

$$
A+B=
\begin{pmatrix}
10 & 12 & 14 \\
16 & 18 & 20
\end{pmatrix}
$$

## Índice
- [Ejercicio 1: Determinantes](#ejercicio-1-determinantes)
- [Ejercicio 2: Método de Sarrus y Cofactores](#ejercicio-2-cofactores-y-metodo-sarrus)
- [Ejercicio 3: Aplicación a vectores y propiedades](#ejercicio-3--aplicacion-a-vectores-y-propidades)

---

# Ejercicio 1: Determinantes

## Objetivo del ejercicio

El objetivo es aprender a calcular determinantes, comprender su utilidad para identificar si una matriz es invertible y aplicarlo para resolver sistemas lineales o problemas geométricos.

### a)

$$
A=
\begin{pmatrix}
5 & 2 \\
3 & 1
\end{pmatrix}
$$

$$
\det(A)=5(1)-2(3)=5-6=-1
$$

$$
\boxed{-1}
$$

### b)

$$
B=
\begin{pmatrix}
-1 & 4 \\
2 & -8
\end{pmatrix}
$$

$$
\det(B)=(-1)(-8)-4(2)=8-8=0
$$

$$
\boxed{0}
$$

### c)

$$
C=
\begin{pmatrix}
6 & 9 \\
2 & 3
\end{pmatrix}
$$

$$
\det(C)=6(3)-9(2)=18-18=0
$$

$$
\boxed{0}
$$

### d)

$$
D=
\begin{pmatrix}
0 & 5 \\
-5 & 0
\end{pmatrix}
$$

$$
\det(D)=0(0)-5(-5)=25
$$

$$
\boxed{25}
$$

---

# Ejercicio 2: Cofactores y método Sarrus

## A) Primera matriz

$$
A=
\begin{pmatrix}
1 & 2 & 3 \\
0 & 1 & 4 \\
5 & 6 & 0
\end{pmatrix}
$$

### Paso 1: Repetir columnas

$$
\begin{pmatrix}
1 & 2 & 3 & 1 & 2 \\
0 & 1 & 4 & 0 & 1 \\
5 & 6 & 0 & 5 & 6
\end{pmatrix}
$$

### Paso 2: Diagonales principales

- \(1\cdot1\cdot0=0\)
- \(2\cdot4\cdot5=40\)
- \(3\cdot0\cdot6=0\)

Suma:

$$40$$

### Paso 3: Diagonales secundarias

- \(3\cdot1\cdot5=15\)
- \(6\cdot4\cdot1=24\)
- \(0\cdot0\cdot2=0\)

Suma:

$$39$$

### Paso 4: Determinante

$$
\det(A)=40-39=1
$$

$$
\boxed{1}
$$

---

## B) Segunda matriz

$$
B=
\begin{pmatrix}
2 & -1 & 3 \\
1 & 4 & 0 \\
3 & 2 & -2
\end{pmatrix}
$$

### Paso 1: Repetir columnas

$$
\begin{pmatrix}
2 & -1 & 3 & 2 & -1 \\
1 & 4 & 0 & 1 & 4 \\
3 & 2 & -2 & 3 & 2
\end{pmatrix}
$$

### Paso 2: Diagonales principales

- \(2\cdot4\cdot(-2)=-16\)
- \((-1)\cdot0\cdot3=0\)
- \(3\cdot1\cdot2=6\)

Suma:

$$-10$$

### Paso 3: Diagonales secundarias

- \(3\cdot4\cdot3=36\)
- \((-2)\cdot0\cdot2=0\)
- \((-2)\cdot1\cdot(-1)=2\)

Suma:

$$38$$

### Determinante

$$
\det(B)=-10-38=-48
$$

$$
\boxed{-48}
$$

---

## Ejercicio de Cofactor

$$
C=
\begin{pmatrix}
1 & 0 & 2 \\
-1 & 3 & 1 \\
2 & 0 & 1
\end{pmatrix}
$$

### Cofactores de la primera fila

#### Cofactor de \(a_{11}=1\)

Menor:

$$
\begin{pmatrix}
3 & 1 \\
0 & 1
\end{pmatrix}
$$

Determinante:  
\(3(1)-1(0)=3\)

Cofactor:  
\((−1)^{1+1}3=3\)

#### Cofactor de \(a_{12}=0\)

Menor:

$$
\begin{pmatrix}
-1 & 1 \\
2 & 1
\end{pmatrix}
$$

Determinante:  
\((-1)(1)-1(2)=-3\)

Cofactor:  
\((−1)^{1+2}(-3)=3\)

#### Cofactor de \(a_{13}=2\)

Menor:

$$
\begin{pmatrix}
-1 & 3 \\
2 & 0
\end{pmatrix}
$$

Determinante:  
\(-1(0)-3(2)=-6\)

Cofactor:  
\((−1)^{1+3}(-6)=-6\)

### Determinante total

$$
\det(C)=1(3)+0(3)+2(-6)=3-12=-9
$$

$$
\boxed{-9}
$$

---

# Ejercicio 3:  Aplicación a vectores y propiedades

### Matrices dadas:

$$
A=\begin{pmatrix}2&1\\1&3\end{pmatrix},\quad 
B=\begin{pmatrix}1&2\\3&1\end{pmatrix}
$$

## Propiedad 1: \(\Delta(AB)=\Delta(A)\cdot\Delta(B)\)

### Determinantes individuales

$$\det(A)=6-1=5$$

$$\det(B)=1-6=-5$$

### Producto \(AB\)

$$
AB=
\begin{pmatrix}
5 & 5 \\
10 & 5
\end{pmatrix}
$$

### Determinante

$$
\det(AB)=25-50=-25
$$

Comparación:

$$
5\cdot(-5)=-25
$$

Cumple.

---

## Propiedad 2: \(\Delta(A^T)=\Delta(A)\)

Como \(A\) es simétrica:

$$A^T=A$$

Entonces:

$$\det(A^T)=\det(A)=5$$

---

## Determinante de matriz formada por vectores

Vectores:

\(\mathbf{u}=(3,2),\ \mathbf{v}=(1,4)\)

Matriz:

$$
A=
\begin{pmatrix}
3 & 1 \\
2 & 4
\end{pmatrix}
$$

Determinante:

$$
12-2=10
$$

Área:

$$
|\det(A)|=10
$$

---

## Intercambiar los vectores

$$
A'=
\begin{pmatrix}
1 & 3 \\
4 & 2
\end{pmatrix}
$$

$$
\det(A')=2-12=-10
$$

Área:

$$
|-10|=10
$$

---

## Signo del determinante

- Positivo → orientación antihoraria  
- Negativo → orientación horaria

---

# Conclusión

Aprendí cómo el signo del determinante refleja la orientación geométrica entre vectores y cómo las propiedades del determinante se relacionan entre sí al resolver problemas. El método de Sarrus fue más claro cuando pasé los ejercicios a StackEdit, lo que me ayudó a corregir errores y entender mejor el proceso.

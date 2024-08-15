# 1A Actividad: Álgebra lineal aplicada a los sistemas dinámicos

- Maestría en Sistemas Inteligentes Embebidos
- Materia: Métodos Matemáticos
- Unidad: Álgebra lineal
- Docente: Dr. Juliho Castillo Colmenares
- Puntaje total: 15

## Objetivo

Aplicar los conceptos de álgebra lineal en el la resolución de ecuaciones diferenciales. 

## Instrucciones

- Consulta [Kelley, 2013], capítulos 1 y 2.
- Redacta tus respuestas en formato Markdown.
- Puedes utilizar Python para resolver los problemas. 
- Si utilizas Python, utiliza la sintaxis de Markdown para Python.
- En este caso, también adjunta el código en archivos `.py`. 
- Si la respuesta carece de justificación, no se considerará correcta.
- Exporta y entrega tu trabajo en formato PDF.

### Problemas



#### Problema 1 (3 puntos)

Utilizando [Kelley, 2013], teorema 2.14, resuelve la siguiente ecuación diferencial: $x'= Ax$, donde $A$ es la matriz

$$
\begin{bmatrix}
3 & 2 & 4 \\
2 & 0 & 2 \\
4 & 2 & 3 
\end{bmatrix}
$$

#### Problema 2 (3 puntos)

Utilizando [Kelley, 2013], teorema 2.14, resuelve la siguiente ecuación diferencial: $x'= Ax$, donde $A$ es la matriz

$$
\begin{bmatrix}
0 & 9 \\
-9 & 0
\end{bmatrix}
$$

#### Problema 3 (3 puntos)

Utiliza [Kelley. 2013], teorema 2.14, para encontrar la matriz fundamental de la ecuación diferencial $x'= Ax$, donde $A$ es la matriz

$$
\begin{bmatrix}
4 & 0 & 0 \\
0 & 5 & 1 \\
0 & 1 & 5
\end{bmatrix}
$$

#### Problema 4

##### Inciso 4.1 ( 1.5 puntos)

Muestra que la función matricial  $\Phi$ definida por 
$$
\Phi(t) := 
\begin{bmatrix}
e^{-t} & 2 \\
1 & e^{t}
\end{bmatrix}
$$

para $t \in \R$ es una matriz fundamental para ecuación diferencial 

$$
x' =
\begin{bmatrix}
1 & -2e^{-t} \\
e^{t} & -1
\end{bmatrix} x
$$

##### Inciso 4.2 (1.5 puntos)

Encuentra la solución que satisface la condicional inicial 
$$
x(0) = 
\begin{bmatrix}
1 \\
-1
\end{bmatrix}
$$

#### Problema 5 (3 puntos)

Utiliza el algoritmo de Putzer ([Keller, 2013], teorema 2.33) para encontrar $e^{At}$, donde $A$ es la matriz
$$
\begin{bmatrix}
4 & 0 & 0 \\
0 & 5 & 1 \\
0 & 1 & 5
\end{bmatrix}
$$

## Bibliografía
- Fuhrer, C., Solem, J. E., Verdier, O. (2021). Scientific Computing with Python - Second Edition: High-Performance Scientific Computing with NumPy, SciPy, and Pandas. India: Packt Publishing.
- Grossman, S. I. (2008). Álgebra lineal. Spain: McGraw-Hill Interamericana de España S.L.
- Hirsch, M. W., Smale, S., Devaney, R. L. (2004). Differential Equations, Dynamical Systems, and an Introduction to Chaos. Germany: Elsevier Science.
- Johansson, R. (2018). Numerical Python: Scientific Computing and Data Science Applications with Numpy, SciPy and Matplotlib. Germany: Apress.
- Kelley, W. G., Peterson, A. C. (2010). The Theory of Differential Equations: Classical and Qualitative. United States: Springer New York.
- Kelley, W. G. (2013). Solving Differential Equations with Linear Algebra. United States: Society for Industrial and Applied Mathematics.
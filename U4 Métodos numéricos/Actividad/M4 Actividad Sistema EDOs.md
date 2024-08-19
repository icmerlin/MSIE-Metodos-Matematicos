

# 4A Problemario: Solución Numérica de Sistemas de Ecuaciones Diferenciales Ordinarias

- Maestría en Sistemas Inteligentes Embebidos
- Materia: Métodos matemáticos
- Unidad: Métodos numéricos
- Docente: Dr. Juliho Castillo Colmenares
- Puntaje total: 15

## Objetivo

Aplicar y analizar diferentes métodos numéricos para resolver sistemas de ecuaciones diferenciales ordinarias.

## Instrucciones

- Consulta [Fuhrer et al., 2021], [Johansson, 2018], [Linge & Langtangen, 2016], y [Tveito et al., 2010].
- Redacta tus respuestas en formato Markdown.
- Puedes utilizar Python para resolver los problemas.
- Si utilizas Python, utiliza la sintaxis de Markdown para Python.
- En este caso, también adjunta el código en archivos `.py`.
- Si la respuesta carece de justificación, no se considerará correcta.
- Exporta y entrega tu trabajo en formato PDF.

## Problemas

#### Problema 1. 

- Para cada sistema de ecuaciones diferenciales ordinarias, aplica un método numérico para encontrar una solución aproximada.
- Dibuja las soluciones obtenidas.

##### Inciso 1.1 (3 puntos)

$$
\begin{align*}
x' &= y \\
y' &= -x
\end{align*}
$$

##### Inciso 1.2 (3 puntos)

$$
\begin{align*}
x' &= x + y \\
y' &= x - y
\end{align*}
$$

#### Problema 2. (4.5 puntos)

- Aplica un método numérico para resolver el siguiente problema de valor inicial.
- Dibuja la solución obtenida.

$$
\begin{align*}
x' &= x^2 + y \\
y' &= x + y^2 \\
x(0) &= 1, \quad y(0) = 0
\end{align*}
$$

#### Problema 3. (4.5 puntos)

- Encuentra una solución aproximada del siguiente sistema de ecuaciones diferenciales ordinarias utilizando un método numérico. 
- Dibuja la solución obtenida.

$$
\begin{align*}
x' &= x + y \\
y' &= x - y^2 \\
x(0) &= 1, \quad y(0) = 2
\end{align*}
$$

## Bibliografía

1. Fuhrer, C., Solem, J. E., Verdier, O. (2021). Scientific Computing with Python - Second Edition: High-Performance Scientific Computing with NumPy, SciPy, and Pandas. India: Packt Publishing.
2. Johansson, R. (2018). Numerical Python: Scientific Computing and Data Science Applications with Numpy, SciPy and Matplotlib. Germany: Apress.
3. Linge, S., Langtangen, H. P. (2016). Programming for Computations - Python: A Gentle Introduction to Numerical Simulations with Python. Germany: Springer International Publishing.
4. Tveito, A., Langtangen, H. P., Nielsen, B. F., Cai, X. (2010). Elements of Scientific Computing. Germany: Springer.
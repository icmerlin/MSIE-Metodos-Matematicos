# 2A Actividad: Análisis de sistemas dinámicos

- Maestría en Sistemas Inteligentes Embebidos
- Materia: Métodos Matemáticos
- Unidad: Cálculo
- Docente: Dr. Juliho Castillo Colmenares
- Puntaje: 15

## Objetivo

Analizar sistemas dinámicos lineales de forma cualitativa y cuantitativa

## Instrucciones 

- Consulta [Kelley, 2013], capítulos 1 y 2.
- Redacta tus respuestas en formato Markdown.
- Puedes utilizar Python para resolver los problemas. 
- Si utilizas Python, utiliza la sintaxis de Markdown para Python.
- En este caso, también adjunta el código en archivos `.py`. 
- Si la respuesta carece de justificación, no se considerará correcta.
- Exporta y entrega tu trabajo en formato PDF.

## Problemas

#### Problema 1.

- Para cada sistema, determina si es hamiltoniano.
- Si es hamiltoniano, construye la función hamiltoniana paso a paso y verifica que sea tu construcción sea correcta. 
- En otro caso, explica porque el sistema no podría ser hamiltoniano. 

##### Inciso 1.1 (1.5 puntos)

$$
x'= e^{y}-2x \\
y'= 2y-2x
$$

##### Inciso 1.2 (1.5 puntos)

$$
x'=x+y\\
y'=-x+y
$$



#### Problema 2

- Dibuja los diagramas del plano fase para cada uno de los siguientes sistemas. 
- Determina los puntos críticos y clasifícalos.

##### Inciso 2.1 (1.5 puntos)

$$
\begin{bmatrix}
x' \\
y'
\end{bmatrix}
= 
\begin{bmatrix}
0 & 4 \\
-4 & 0 
\end{bmatrix}
\begin{bmatrix}
x \\
y
\end{bmatrix}
$$

##### Inciso 2.2 (1.5 puntos)

$$
\begin{bmatrix}
x' \\
y'
\end{bmatrix}
= 
\begin{bmatrix}
0 & 4 \\
-1 & 0 
\end{bmatrix}
\begin{bmatrix}
x \\
y
\end{bmatrix}
$$

##### Inciso 2.3 (1.5 puntos)

$$
\begin{bmatrix}
x' \\
y'
\end{bmatrix}
= 
\begin{bmatrix}
-8 & 10 \\
-4 & 4 
\end{bmatrix}
\begin{bmatrix}
x \\
y
\end{bmatrix}
$$



##### Inciso 2.4 (1.5 puntos)

$$
\begin{bmatrix}
x' \\
y'
\end{bmatrix}
= 
\begin{bmatrix}
-1 & -5 \\
2 & 5 
\end{bmatrix}
\begin{bmatrix}
x \\
y
\end{bmatrix}
$$

#### Problema 3 (1.5 puntos)

Encuentra las constantes $\alpha$ y $\beta$ de manera que 
$$
V(x,y) := \alpha x^2 + \beta y^2 
$$
defina una función de Liapunov para el sistema
$$
x' = -x-5y \\
y' = 3x-y^3
$$

#### Problema 4 (1.5 puntos)

Encuentra una   función de Liapunov para el sistema 

$$
x'=-x-y^2\\
y'=-\dfrac{1}{2}y+2xy
$$

Identifica una familia de conjuntos positivamente invariantes

#### Problema 5

Aplica el teorema de invarianza de LaSalle a cada uno de lo siguientes sistemas y determina que puntos son atraídos hacia el origen

##### Inciso 5.1 (1.5 puntos)

$$
x' = -2x-2xy\\
y' = 2x^2-y
$$

##### Inciso 5.2 (1.5 puntos)

$$
x' = y \\
y' = -x+y^5-2y
$$



## Bibliografía

1. Fuhrer,     C., Solem, J. E., Verdier, O. (2021). Scientific Computing with Python -     Second Edition: High-Performance Scientific Computing with NumPy, SciPy,     and Pandas. India: Packt Publishing.
2. Hirsch, M.     W., Smale, S., Devaney, R. L. (2004). Differential Equations, Dynamical     Systems, and an Introduction to Chaos. Germany:     Elsevier Science.
3. Johansson,     R. (2018). Numerical Python: Scientific Computing and Data Science     Applications with Numpy, SciPy and Matplotlib. Germany: Apress.
4. Kelley, W. G., Peterson, A. C. (2010). The Theory of Differential Equations: Classical and Qualitative. United States: Springer New York.
5. Stewart, J. (2016). Calculus: Early Transcendentals. United States: Cengage Learning.




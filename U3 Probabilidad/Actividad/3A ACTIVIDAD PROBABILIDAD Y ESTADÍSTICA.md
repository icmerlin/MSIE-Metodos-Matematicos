# 3A Actividad: Sistemas dinámicos aleatorios

- Maestría en Sistemas Inteligentes Embebidos
- Materia: Métodos Matemáticos
- Unidad: Probabilidad y estadística
- Docente: Dr. Juliho Castillo Colmenares
- Puntaje total: 15

## Objetivo

Analizar sistemas dinámicos aleatorios de forma cualitativa y cuantitativa

## Bibliografía

- Hoel, P. G., Port, S. C., Stone, C. J. (1971). Introduction to Probability Theory. Taiwan: Houghton Mifflin.
- Hoel, P. G. (1954). Introduction to mathematical statistics. United Kingdom: Wiley.
- Hoel, P. G., Port, S. C., & Stone, C. J. (1986). Introduction to Stochastic Processes. Waveland Press.
- Taha, H. A. (2018). Operations Research: An Introduction, Global Edition. United Kingdom: Pearson Education.

## Instrucciones 

- Consulta [Hoel, et. al. (1986)], capítulos 1 y 2
- Redacta tus respuestas en formato Markdown.
- Puedes utilizar Python para resolver los problemas. 
- Si utilizas Python, utiliza la sintaxis de Markdown para Python.
- En este caso, también adjunta el código en archivos `.py`. 
- Si la respuesta carece de justificación, no se considerará correcta.
- Exporta y entrega tu trabajo en formato PDF.

## Problemas

### Problema 1 (1.5 puntos)

Considere la cadena de Markov con espacio de estados $\{0,1,2\}$ y matriz de transición
$$
T = \begin{bmatrix}
0.4 & 0.4 & 0.2 \\
0.3 & 0.4 & 0.3 \\
0.2 & 0.4 & 0.4
\end{bmatrix}
$$
donde la probabilidad de transición $P(x,y)$ de pasar del estado $x$ al estado $y$ está dado por $T_{x,y}$. 

Muestre que esta cadena tiene una distribución estacionaria $\pi$ única y encuentre $\pi$.

### Problema 2

Considere una cadena de Markov que tiene un espacio de estados $\{0,1,...,6\}$ y matriz de transición
$$
T = \begin{bmatrix}
1/2 & 0 & 1/8 & 1/4 & 1/8 & 0 & 0 \\
0 & 0 & 1 & 0 & 0 & 0 & 0 \\
0 & 0 & 0 & 1 & 0 & 0 & 0 \\
0 & 1 & 0 & 0 & 0 & 0 & 0 \\
0 & 0 & 0 & 0 & 1/2 & 0 & 1/2 \\
0 & 0 & 0 & 0 & 1/2 & 1/2 & 0 \\
0 & 0 & 0 & 0 & 0 & 1/2 &  1/2 \\
\end{bmatrix}
$$
donde la probabilidad de transición $P(x,y)$ de pasar del estado $x$ al estado $y$ está dado por $T_{x,y}$.

#### Inciso 2.1(1.5 puntos)

Determine cuales estados son de transición y cuales son recurrentes

#### Inciso 2.2(1.5 puntos)

Encuentre $\rho_{0,y}$ para $y=0,...,6$, donde $\rho_{x,y}$ es la probabilidad de que una cadena que comienza en $x$ visite alguna vez $y$.

#### Inciso 2.3(1.5 puntos)

Encuentre la distribución estacionaria concentrada en cada uno de los conjuntos cerrados irreducibles. 

#### Inciso 2.4(1.5 puntos)

Encuentra $\lim_{n\to\infty} G_n(x,y)/n$, donde $G(x,y)$ es el número esperado de visitas a $y$ para  una cadena que comienza en $x$.

### Problema 3

Sea $X_{n}, n\geq 0$, la cadena de Ehrenfest con $d=4$ y $X_0=0$.

#### Inciso 3.1(1.5 puntos)

Encuentre la distribución aproximada de $X_n$ para $n$ muy grande y  par.

#### Inciso 3.2(1.5 puntos)

Encuentre la distribución aproximada de $X_n$ para $n$ muy grande e  impar.

### Problema 4

Considere la cadena de Markov en $\{0,1,2\}$ que tiene matriz de transición 
$$
\begin{bmatrix}
0 & 0 & 1 \\
1 & 0 & 0 \\
\frac{1}{2} & \frac{1}{2} & 0
\end{bmatrix}
$$
donde la probabilidad de transición $P(x,y)$ de pasar del estado $x$ al estado $y$ está dado por $T_{x,y}$.

#### Inciso 4.1(1.5 puntos)

Muestre que la cadena es irreducible.

#### Inciso 4.2(1.5 puntos)

Encuentre el periodo

#### Inciso 4.3(1.5 puntos)

Encuentre el estado estacionario


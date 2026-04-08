## Estadística Inferencial

En este módulo se introducen herramientas fundamentales de la estadística inferencial mediante ejemplos prácticos implementados en Python. El enfoque combina modelado probabilístico, simulaciones y métodos de estimación para comprender cómo extraer conclusiones a partir de datos muestrales.

---

### 🔎 Distribuciones probabilísticas

Se estudia una muestra aleatoria $X_1, \dots, X_n$ cuya función de densidad depende del parámetro $\theta$:

$$
f_X(x;\theta)=
\begin{cases}
\theta x^{\theta-1} & 0 < x < 1,\ \theta > 0 \\
0 & \text{en otro caso}
\end{cases}
$$

Además, se analiza la **distribución Beta**, empleando librerías como `NumPy`, `SciPy` y `Matplotlib` para:

- Simular observaciones aleatorias  
- Representar funciones de densidad  
- Examinar el efecto de los parámetros en la forma de la distribución  

---

### 🎲 Experimentos de simulación

Se realizan simulaciones con distintas distribuciones de probabilidad, entre ellas:

- t de Student  
- Beta  
- Lognormal  
- Gamma  
- Poisson  
- Exponencial  

Estas simulaciones permiten observar el comportamiento de las muestras y analizar la evolución de la **media muestral**, evidenciando la convergencia hacia el valor esperado teórico, en concordancia con la Ley de los Grandes Números.

---

### 📉 Representación gráfica

Mediante el uso de **Matplotlib**, se generan visualizaciones que incluyen:

- Datos simulados  
- Trayectorias de la media acumulada  
- Comparaciones entre media empírica y media teórica  

Estas representaciones facilitan la interpretación del comportamiento estadístico de los datos.

---

### 📏 Estimación por Máxima Verosimilitud

Se introduce el método de **Máxima Verosimilitud (MLE)** para estimar parámetros desconocidos.

Sea la variable aleatoria discreta $X$ con la siguiente distribución:

$$
\begin{align*}
P(X=0)&=\frac{2}{3}\theta,\\
P(X=1)&=\frac{1}{3}\theta,\\
P(X=2)&=\frac{2}{3}(1-\theta),\\
P(X=3)&=\frac{1}{3}(1-\theta)
\end{align*}
$$

y la muestra observada:

$$
(3, 0, 2, 1, 3, 2, 1, 0, 2, 1)
$$

La función de verosimilitud queda expresada como:

$$
L(\theta) = \frac{32}{243}\theta^{5}(1-\theta)^{5}
$$

Tomando logaritmos se obtiene:

$$
\log L(\theta) = \log(32/243) + 5\log(\theta) + 5\log(1-\theta)
$$

Al derivar y maximizar la expresión anterior, se obtiene el estimador:

$$
\hat{\theta} = 0.5
$$

El resultado corresponde a un máximo, lo cual se verifica evaluando la segunda derivada de la log-verosimilitud.

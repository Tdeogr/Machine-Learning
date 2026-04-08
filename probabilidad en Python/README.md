## Probabilidad en Python

Esta sección explora conceptos fundamentales de **probabilidad** mediante su implementación directa en Python. El objetivo es comprender los principios teóricos a través de la programación, construyendo soluciones desde cero y analizando los resultados obtenidos.

Se desarrollan distintos ejemplos prácticos donde se implementan funciones sin depender de librerías especializadas. Entre los problemas estudiados se incluyen:

- Extracción de urnas  
- Problema de Newton aplicado al lanzamiento de dados  

Estos ejercicios permiten entender el razonamiento probabilístico paso a paso, reforzando el aprendizaje mediante código.

---

### 📊 Visualización de conceptos probabilísticos

Además del cálculo analítico, se incorporan representaciones gráficas para facilitar la interpretación de los resultados. Se analizan elementos como:

- Frecuencias relativas  
- Distribuciones de probabilidad  
- Esperanza matemática  
- Varianza  

Para ello se utilizan herramientas como **NumPy** y **Matplotlib**, que permiten simular experimentos y visualizar su comportamiento.

---

### 🎲 Muestreo aleatorio con NumPy

Se introduce el muestreo aleatorio a través del **Ensayo de Bernoulli**, utilizando el ejemplo clásico del lanzamiento de una moneda. En este caso:

- Espacio muestral: $\Omega = \{\text{águila}, \text{sol}\}$  
- Variable aleatoria: $X:\Omega \to \{0,1\}$  
- Probabilidades asignadas:  
  - $\mathbb{P}(X(\text{sol}) = 1) = p \in (0,1)$  
  - $\mathbb{P}(X(\text{águila}) = 0) = 1 - p \in (0,1)$  

Este enfoque permite simular múltiples experimentos y estudiar la variabilidad de los resultados mediante programación.

---

### 🎯 Ruina del jugador

También se aborda el problema de la **ruina del jugador**, un modelo clásico que describe la evolución del capital de un individuo que participa en apuestas repetidas. Este análisis permite calcular la probabilidad de que el jugador pierda todo su capital o alcance un objetivo determinado, dependiendo de sus probabilidades de éxito y de su capital inicial.

---

### 🧠 Enfoque general

En conjunto, esta sección combina teoría y simulación computacional, mostrando cómo Python puede utilizarse para estudiar fenómenos probabilísticos y analizar resultados de forma intuitiva.

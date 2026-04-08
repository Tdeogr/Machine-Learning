## Cálculo Estocástico

Este apartado presenta una introducción al **cálculo estocástico**, combinando teoría de probabilidad avanzada con el estudio de procesos aleatorios. Se abordan los conceptos fundamentales necesarios para modelar fenómenos dinámicos sujetos a incertidumbre.

---

### 🎲 Probabilidad avanzada

El punto de partida es la formalización de los espacios probabilísticos, definidos como $(\Omega, \mathcal{F}, P)$. En este contexto se revisan conceptos clave como:

- Espacios de probabilidad completos  
- Conjuntos de medida cero  
- Importancia de la completitud en la teoría de la medida  

Un espacio de probabilidad se considera completo cuando cualquier subconjunto de un evento con probabilidad nula también pertenece a la sigma-álgebra. Esta propiedad resulta esencial para el desarrollo riguroso de procesos estocásticos.

---

### ⏱️ Variables exponenciales y tiempos de espera

Se analizan variables aleatorias continuas, especialmente la **distribución exponencial**, ampliamente utilizada para modelar tiempos entre eventos. Se estudian sus propiedades y el comportamiento de relojes exponenciales independientes.

Si $T_1, \dots, T_n$ son variables independientes con distribución exponencial, entonces:

$$
T = \min\{T_1, \dots, T_n\}
$$

representa el instante del primer evento en un sistema con múltiples procesos aleatorios.

---

### 🔄 Cadenas de Markov en tiempo continuo

Se introducen procesos de Markov en tiempo continuo, incluyendo:

- Definición formal del proceso  
- Interpretación mediante tiempos de permanencia  
- Tiempos medios de transición  
- Clasificación de estados  
- Procesos de nacimiento y muerte  
- Procesos de nacimiento puro  

También se estudian las ecuaciones **forward** y **backward**, que describen la evolución temporal de las probabilidades del sistema.

---

### 🌊 Movimiento Browniano

El **movimiento browniano** se presenta como uno de los procesos fundamentales del cálculo estocástico. Se revisan sus principales propiedades:

- Incrementos independientes  
- Incrementos estacionarios  
- Distribución normal de los incrementos  

Si $B_t$ representa un movimiento browniano, entonces:

$$
B_t - B_s \sim \mathcal{N}(0, t - s)
$$

Además, se analizan propiedades adicionales y su relación con procesos gaussianos.

---

### 🎯 Martingalas

Se introduce el concepto de **martingala**, esencial en la teoría moderna de probabilidad. Se estudian:

- Definición formal  
- Propiedades básicas  
- Interpretación como procesos sin tendencia  

Las martingalas tienen aplicaciones importantes en finanzas, teoría de juegos y modelado de sistemas aleatorios.

---

### ∫ Integración estocástica

Se construye la integral estocástica de forma progresiva:

- Definición inicial para procesos simples  
- Extensión mediante convergencia en $L^2$  
- Integración respecto al movimiento browniano  

Esta construcción permite desarrollar herramientas fundamentales del cálculo estocástico moderno.

---

### 🌐 Aplicaciones

El cálculo estocástico se aplica en diversas áreas, entre ellas:

- Finanzas cuantitativas  
- Modelos de difusión  
- Inteligencia Artificial  
- Procesos de decisión  

También se analizan ejemplos prácticos como procesos de nacimiento y muerte y modelos dinámicos bajo incertidumbre.

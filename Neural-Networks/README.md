## Redes Neuronales

Esta sección aborda la aplicación de **redes neuronales artificiales** en problemas de clasificación, utilizando Python junto con la librería *scikit-learn*. El objetivo es comprender cómo estos modelos aprenden patrones complejos a partir de los datos.

Para facilitar el análisis, se emplean conjuntos de datos simulados generados mediante técnicas de *clustering*. Estos datos permiten observar gráficamente la separación entre clases y entender el nivel de dificultad del problema antes del entrenamiento del modelo.

---

### 🧠 Modelo MLPClassifier

Se implementa un clasificador basado en perceptrones multicapa (**MLPClassifier**), experimentando con diferentes configuraciones de la red. Se modifican aspectos como:

- Número de capas ocultas  
- Cantidad de neuronas por capa  
- Profundidad del modelo  

Estas variaciones permiten analizar cómo la arquitectura influye en la capacidad de aprendizaje y en la generalización del modelo.

Las redes neuronales utilizadas funcionan mediante capas de neuronas artificiales conectadas entre sí, donde cada capa transforma la información hasta producir una predicción final.

---

### 📉 Función de pérdida

Durante el entrenamiento se utiliza la **entropía cruzada** como función de pérdida, la cual evalúa la diferencia entre las probabilidades predichas por el modelo y las etiquetas reales. Este criterio es ampliamente empleado en tareas de clasificación supervisada.

---

### ⚙️ Hiperparámetros relevantes

Se estudia el impacto de distintos parámetros que afectan el desempeño del modelo, entre ellos:

- **Learning rate**: controla la magnitud de los ajustes en los pesos  
- Número de iteraciones (*epochs*)  
- Tamaño de la red neuronal  
- Profundidad del modelo  

La correcta elección de estos valores resulta clave para lograr un buen rendimiento.

---

### 🔍 Optimización del modelo

Para encontrar configuraciones adecuadas, se aplican técnicas de búsqueda y validación como:

- **Grid Search**  
- **Randomized Search**  
- Validación cruzada (*K-Fold*)  

Estos métodos permiten evaluar múltiples combinaciones de hiperparámetros y seleccionar aquellas que mejor generalizan.

---

### 📊 Visualización

La interpretación de los resultados se apoya en gráficos generados con **Matplotlib** y **Seaborn**, los cuales permiten observar:

- Distribución de los datos  
- Fronteras de decisión  
- Desempeño del modelo  

---

### 🧩 Conclusión

En conjunto, esta sección introduce los fundamentos del uso de redes neuronales para clasificación, destacando la importancia de la arquitectura del modelo, la selección de hiperparámetros y la evaluación adecuada para obtener resultados confiables.

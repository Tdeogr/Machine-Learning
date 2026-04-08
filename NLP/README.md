## Procesamiento de Lenguaje Natural (NLP)

Esta sección introduce conceptos esenciales del **Procesamiento de Lenguaje Natural**, centrados en el análisis y transformación de información textual mediante herramientas de Python. El objetivo principal es convertir el lenguaje humano en estructuras que puedan ser interpretadas y analizadas por algoritmos.

El texto constituye una fuente importante de datos no estructurados dentro de la ciencia de datos. Debido a ello, es necesario aplicar técnicas que permitan limpiar, organizar y representar la información contenida en cadenas de caracteres, facilitando su uso en tareas analíticas y predictivas.

---

### 🧩 Representación de texto

Se exploran diferentes métodos para transformar documentos en representaciones matemáticas, entre ellos:

- **LSI (Latent Semantic Indexing)**  
- **LDA (Latent Dirichlet Allocation)**  

Estos enfoques permiten descubrir patrones y temas ocultos dentro de colecciones de documentos, ayudando a comprender la estructura semántica del texto y mejorar su organización.

---

### 🔤 Word Embeddings

También se emplean **embeddings de palabras** mediante el modelo **FastText**, que convierte cada término en un vector numérico dentro de un espacio continuo. Esta representación permite capturar similitudes semánticas y relaciones lingüísticas entre palabras.

Los embeddings resultan útiles en diversas aplicaciones como:

- Clasificación de documentos  
- Análisis de sentimientos  
- Agrupamiento de textos  

---

### ⚙️ Preprocesamiento del texto

Antes del modelado, el texto requiere una etapa de normalización. En este proceso se aplican técnicas como:

- **Stemming**: reducción de palabras a su raíz mediante reglas simples.  
- **Lematización**: conversión de palabras a su forma base considerando su contexto gramatical.  

Ambos métodos ayudan a reducir la variabilidad lingüística, permitiendo que distintas formas de una misma palabra se traten como un solo token.

---

### 😊 Análisis de sentimientos

Como aplicación práctica, se desarrolla el **análisis de sentimientos**, donde textos como reseñas u opiniones son clasificados según su polaridad (positiva o negativa). Para ello, se utilizan tanto técnicas tradicionales de representación como embeddings modernos.

---

### 🧠 Conclusión

En conjunto, esta sección cubre las etapas principales del flujo de trabajo en NLP: preprocesamiento, representación semántica y aplicación de modelos. Esto permite trabajar de manera efectiva con datos textuales y extraer información valiosa a partir del lenguaje natural.

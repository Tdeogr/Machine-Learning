## Series de Tiempo

Este apartado introduce el análisis de **series temporales**, combinando conceptos teóricos con su aplicación práctica en Python para estudiar y predecir datos que evolucionan a lo largo del tiempo.

---

### ⏳ Concepto de serie temporal

Una serie de tiempo consiste en un conjunto de observaciones registradas de manera secuencial en distintos instantes. Estos registros suelen tomarse en intervalos regulares, como:

- Horas  
- Días  
- Semanas  
- Meses  
- Trimestres  
- Años  

El propósito principal es analizar la dinámica temporal de los datos para identificar patrones y generar pronósticos.

---

### 📊 Exploración y visualización

El estudio inicial de una serie temporal incluye técnicas que permiten:

- Detectar tendencias de largo plazo  
- Identificar patrones estacionales  
- Analizar fluctuaciones o ruido  
- Reconocer comportamientos recurrentes  

Generalmente, estas series se representan mediante **gráficos de líneas**, los cuales facilitan la interpretación de la evolución de los valores en el tiempo.

---

### 🔮 Pronóstico (Forecasting)

El **forecasting** se refiere al uso de modelos estadísticos o computacionales para estimar valores futuros a partir del historial disponible. Este tipo de análisis es ampliamente utilizado en distintos campos, como:

- Finanzas  
- Economía  
- Machine Learning  
- Monitoreo de sistemas  

---

### 🐍 Aplicación con Python

Para trabajar con datos reales, se emplea Python como herramienta principal para descargar, procesar y modelar series temporales.

#### 📥 Obtención de datos

Se utiliza la librería `yfinance` para descargar información histórica del índice S&P 500:

```python
import yfinance as yf

sp500 = yf.download("^GSPC", start="2000-01-01", end="2014-12-31")

# Producción Diaria de Petróleo en Argentina

Un análisis exploratorio de datos (EDA) realizado con Python y Pandas sobre un conjunto de datos de producción
de petróleo en distintas provincias argentinas. El objetivo del proyecto es comprender la distribución, evolución
y comportamiento de la producción a lo largo del tiempo, detectando valores extremos y patrones generales.

---

# 🛠️ Herramientas Utilizadas
- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib y Seaborn   
- Jupyter Notebook

---

# 🚀 Objetivos del análisis
Este trabajo responde a un conjunto de preguntas clave para entender la estructura del dataset:

- Distribución de los registros por provincia.
- Detección de valores atípicos (outliers) en la producción diaria.
- Comparación de la producción entre provincias.
- Identificación de tendencias o variaciones a lo largo del tiempo.
- Aplicación de técnicas de agrupación (binning) para clasificar los niveles de producción.
- Evaluación del efecto de técnicas de limpieza como el capping (recorte de valores extremos).

## 📊 Conjunto de datos

| Columna | Tipo | Descripción |
|----------|------|-------------|
| anio | int | Año del registro. |
| mes | int | Mes del registro. |
| indice_tiempo | object | Identificador temporal (año-mes). |
| provincia | object | Provincia de origen del registro. |
| produccion_petroleo_promedio_dia_m3 | float | Producción promedio diaria de petróleo en metros cúbicos. |


El análisis permitió identificar diferencias significativas entre provincias y la existencia de valores
extremos que afectaban la lectura del comportamiento general.  
Mediante técnicas como **boxplots, heatmaps, capping** y **binning**, se obtuvo una visión más equilibrada
de los datos, mejorando la comprensión del rango productivo típico y de las provincias más relevantes.

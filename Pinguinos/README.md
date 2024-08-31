# 🐧 Clustering de Pingüinos

Este proyecto aplica técnicas de Machine Learning no supervisadas para analizar un dataset de pingüinos, utilizando K-Means para agrupar a los pingüinos en clusters basados en características físicas como la longitud del culmen, la profundidad del culmen, la longitud de la aleta y la masa corporal.

## 📊 Descripción del Proyecto

El objetivo es descubrir patrones en las características físicas de los pingüinos utilizando algoritmos de clustering. A través de este análisis, buscamos identificar grupos (clusters) de pingüinos con características similares, lo que podría ayudar en estudios de biología y ecología, o en cualquier análisis comparativo entre diferentes especies.

## Pasos del Proyecto

1. **Importación y preprocesamiento de datos:**
   - Limpieza de datos y manejo de valores faltantes.
   - Normalización de los datos numéricos.

2. **Análisis exploratorio:**
   - Visualización de la distribución de variables.
   - Correlación entre características.

3. **Aplicación de K-Means:**
   - Selección del número óptimo de clusters.
   - Asignación de cada pingüino a un cluster.

4. **Visualización de resultados:**
   - Gráficos de dispersión para comparar clusters en diferentes pares de variables.

5. **Cálculo de estadísticos por cluster:**
   - Creación de un DataFrame con los valores promedio de las características originales para cada cluster.

## 📁 Estructura del Proyecto

- `notebook.ipynb`: Notebook de Jupyter que contiene todo el análisis, desde la importación de los datos hasta la visualización de los resultados.
- `penguins.csv`: Archivo CSV con los datos de entrada (si aplicable).
- `README.md`: Este archivo que describe el proyecto.

## 📚 Requisitos

Para ejecutar este proyecto, necesitarás instalar las siguientes dependencias:

```bash
pip install -r requirements.txt

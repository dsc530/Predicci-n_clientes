# Recomendación de Planes Megaline
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Classification-blue)
![Python](https://img.shields.io/badge/Python-3.8%2B-success)

Este proyecto tiene como objetivo entrenar un modelo de machine learning para recomendar el plan de telecomunicaciones más adecuado para cada cliente, según su comportamiento de uso.

## 📋 Descripción
- Procesamos y exploramos los datos de uso de los clientes para entrenar y evaluar modelos de clasificación.
- El modelo con mejor desempeño se valida con el conjunto de prueba y se somete a pruebas de cordura para garantizar su generalización.

## 🎯 Objetivos
- **Preparación de Datos:** Cargar datos desde un CSV, limpiar valores nulos, eliminar duplicados y asegurar el formato correcto de cada columna.
- **Segmentación de Datos:** Dividir el conjunto en entrenamiento (60 %), validación (20 %) y prueba (20 %).
- **Evaluación de Modelos:** Comparar modelos de clasificación (Árbol de Decisión, Bosque Aleatorio y Regresión Logística), incluyendo ajuste de hiperparámetros.
- **Prueba de Cordura:** Seleccionar Bosque Aleatorio, analizar la importancia de las características, probar con datos aleatorios para detectar sobreajuste y realizar validación cruzada.
- **Conclusiones:** Resumir el rendimiento y la idoneidad del modelo seleccionado.

## 🗂️ Estructura del Proyecto
1. **Importación de Datos:** Uso de `pandas` para leer el archivo CSV.
2. **Análisis de Datos:** Comprobación de valores nulos, duplicados y tipos de datos (procesos ETL).
3. **Segmentación de Datos:** División en conjuntos de entrenamiento, validación y prueba.
4. **Calidad de Modelos de Clasificación:** Comparación de exactitud entre Árbol de Decisión, Bosque Aleatorio y Regresión Logística.
5. **Prueba de Cordura:** Importancia de variables, prueba con datos aleatorios y validación cruzada para Bosque Aleatorio.
6. **Resultados y Conclusiones:** Métricas de rendimiento y recomendaciones.

## 📦 Requisitos del Entorno
- Python 3.8 o superior
- Pandas
- Numpy
- Scikit-learn
- Matplotlib

## 🚀 Cómo Clonar el Repositorio
```bash
git clone https://https://github.com/dsc530/Prediccion_clientes
cd megaline-plan-recommendation

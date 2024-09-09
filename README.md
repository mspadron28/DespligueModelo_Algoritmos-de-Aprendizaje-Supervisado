
# Despliegue de Modelos de Algoritmos de Aprendizaje Supervisado

Este proyecto se enfoca en el análisis, limpieza y entrenamiento de datos utilizando diversos algoritmos de **Aprendizaje Supervisado**. El objetivo principal es determinar el mejor modelo basado en métricas de rendimiento, así como evaluar si los modelos sufren de **underfitting** o **overfitting**. Una vez identificado el mejor modelo, se procede a su despliegue local utilizando el dataset entregado.

## Algoritmos Aplicados

El proyecto implementa los siguientes algoritmos de aprendizaje supervisado:

1. **Regresión**: Aplicación de un modelo de regresión (selección de una técnica apropiada).
2. **Máquinas de Soporte Vectorial (SVM)**: Pruebas con 4 kernels diferentes.
3. **k-NN (k-Nearest Neighbors)**: Identificación del mejor valor para "k" mediante pruebas iterativas.
4. **Árboles de Decisión**: Implementación de un modelo basado en árboles de decisión.
5. **Naive Bayes**: Aplicación de este algoritmo para la clasificación.
6. **Redes Neuronales**: Creación de un modelo simple de red neuronal.

## Objetivos del Proyecto

1. **Familiarización con el Dataset**: Análisis exploratorio de los datos y detección de inconsistencias.
2. **Preprocesamiento**: Limpieza de datos y preparación para entrenar los modelos.
3. **Entrenamiento**: Aplicación de los algoritmos supervisados mencionados anteriormente.
4. **Evaluación de Modelos**: 
   - Comparación de los resultados de los modelos utilizando métricas como **precisión**, **recall**, **F1-score**, entre otras.
   - Identificación de **underfitting** y **overfitting**.
5. **Selección del Mejor Modelo**: Basado en el rendimiento y capacidad de generalización.
6. **Despliegue Local del Mejor Modelo**: Creación de un sistema local para desplegar el modelo seleccionado.

## Tecnologías Utilizadas

- **Python**: Lenguaje principal para el análisis de datos y el entrenamiento de los modelos.
- **Librerías**:
  - **scikit-learn**: Para la implementación de los algoritmos de aprendizaje supervisado.
  - **Pandas** y **NumPy**: Para la manipulación y análisis de datos.
  - **Matplotlib** y **Seaborn**: Para visualización de datos y resultados.
  - **TensorFlow/Keras**: Para la creación y entrenamiento de redes neuronales.

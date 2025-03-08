# Proyecto de Análisis y Predicción de Precios de Casas
Michelle Mejía, Silvia Illescas y Emilio Reyes

## Descripción General
Este proyecto tiene como objetivo analizar y predecir los precios de casas utilizando técnicas avanzadas de minería de datos y modelos de aprendizaje automático. Se basa en el conjunto de datos **"House Prices: Advanced Regression Techniques"** de Kaggle, el cual contiene diversas características estructurales, de ubicación y calidad de construcción de viviendas. A lo largo del proyecto, se han explorado múltiples enfoques para entender y modelar la relación entre estas características y el precio de venta de las casas.

## Objetivos del Proyecto
1. **Análisis Exploratorio de Datos (EDA)** para comprender la estructura y distribución de los datos.
2. **Identificación de variables clave** que mejor predicen el precio de las casas.
3. **Implementación de modelos de regresión y clasificación** para la predicción del precio de las viviendas.
4. **Comparación de diferentes modelos de aprendizaje automático**, como regresión lineal, árboles de decisión y Random Forest.
5. **Evaluación y optimización de modelos**, asegurando su reproducibilidad mediante la correcta división de datos en entrenamiento y prueba.

## Entrega 1: Análisis Exploratorio y Modelos de Regresión
En la primera entrega, se realizó un análisis exhaustivo del conjunto de datos:
- **EDA (Análisis Exploratorio de Datos):** Identificación de valores nulos, distribución de variables, pruebas de normalidad y correlación entre variables.
- **Análisis de Clustering:** Agrupación de casas en **tres categorías (económicas, medias y de lujo)** usando **K-Means**.
- **Ingeniería de Características:** Identificación de las variables más influyentes en el precio de las casas mediante **Información Mutua**.
- **Modelado con Regresión Lineal:** Se desarrolló un modelo de regresión lineal utilizando las variables más relevantes.
- **División de Datos en Entrenamiento y Prueba:** Se garantizó la reproducibilidad del análisis utilizando `train_test_split()` con `random_state=42`.

## Entrega 2: Árboles de Decisión y Comparación de Modelos
En esta etapa, se expandió el análisis con modelos basados en **árboles de decisión**:
- **Creación de una variable categórica** que clasifica las casas en **económicas, intermedias y caras** basada en la distribución de precios.
- **Desarrollo de modelos de árboles de regresión** para predecir el precio de venta de las viviendas.
- **Ajuste de hiperparámetros** modificando la profundidad del árbol para encontrar el mejor modelo.
- **Comparación con regresión lineal y Random Forest:** Evaluación del desempeño de los modelos utilizando métricas como RMSE y R².
- **Implementación de Árboles de Clasificación:** Para predecir la categoría de precios de las casas.
- **Matriz de confusión y validación cruzada** para evaluar la precisión de los modelos de clasificación.

## Tecnologías Utilizadas
- **Python** (pandas, numpy, matplotlib, seaborn, scikit-learn)
- **Machine Learning** (Regresión Lineal, Árboles de Decisión, Random Forest, Ingeniería de Características)
- **Visualización de Datos** (Gráficos de correlación, histogramas, scatter plots, heatmaps)

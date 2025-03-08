# Proyecto de Árboles de Decisión para Predicción de Precios de Casas

## Descripción General
Esta etapa del proyecto se centra en la implementación de **Árboles de Decisión** para la predicción del precio de las casas y la clasificación de propiedades en diferentes categorías. Utilizamos el conjunto de datos **"House Prices: Advanced Regression Techniques"** de Kaggle, aplicando técnicas avanzadas de minería de datos y aprendizaje automático.

## Objetivos
1. **Desarrollar modelos de árboles de decisión** para predecir `SalePrice`.
2. **Crear una nueva variable categórica** que agrupe las casas en tres categorías: Económicas, Intermedias y Caras.
3. **Entrenar modelos de clasificación** basados en la nueva variable categórica.
4. **Comparar el desempeño de los modelos** de Árboles de Decisión con Regresión Lineal y Random Forest.
5. **Evaluar la eficiencia de los modelos** mediante métricas de precisión y validación cruzada.

## Actividades Realizadas
- **Uso del mismo conjunto de entrenamiento y prueba** que en la entrega anterior para garantizar la reproducibilidad.
- **Entrenamiento de un Árbol de Regresión** utilizando todas las variables disponibles.
- **Ajuste de la profundidad del árbol** y comparación de modelos con diferentes configuraciones.
- **Evaluación del desempeño** del árbol de regresión en comparación con la regresión lineal.
- **Creación de una variable categórica** basada en los rangos de `SalePrice`, justificando los límites de cada categoría.
- **Entrenamiento de un Árbol de Clasificación** para predecir la categoría de precio de las casas.
- **Evaluación del árbol de clasificación** con una matriz de confusión y análisis de errores.
- **Implementación de Random Forest** como alternativa para mejorar la precisión de la predicción.

## Comparación de Modelos
- **Árboles de Regresión vs. Regresión Lineal**: Se evaluó cuál modelo predice mejor los precios de las casas.
- **Árbol de Clasificación vs. Random Forest**: Se midió la precisión de cada modelo para categorizar las viviendas.

## Tecnologías Utilizadas
- **Python** (pandas, numpy, matplotlib, seaborn, scikit-learn)
- **Machine Learning** (Árboles de Decisión, Random Forest, Ingeniería de Características)
- **Evaluación de Modelos** (Matriz de Confusión, RMSE, R², Validación Cruzada)

## Conclusión
Este análisis permitió evaluar el uso de **Árboles de Decisión** en la predicción de precios y la clasificación de viviendas. Además, la comparación con Regresión Lineal y Random Forest facilitó la identificación del modelo más preciso.

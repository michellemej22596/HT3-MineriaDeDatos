#### Contexto del Proyecto

Este proyecto forma parte del trabajo de consultoría para **InmoValor S.A.**, una empresa del sector inmobiliario que busca mejorar la estimación del precio de las viviendas en Guatemala utilizando técnicas avanzadas de minería de datos. Basados en el conjunto de datos *House Prices: Advanced Regression Techniques* (Kaggle), se han construido y evaluado modelos predictivos en distintas entregas.

En esta entrega, el enfoque está en el uso de **Máquinas Vectoriales de Soporte (SVM)** para:
- Clasificación de precios (barata, media o cara)
- Predicción del precio de venta (regresión)

---

#### Objetivos

- Aplicar modelos de **clasificación SVM** usando la variable categórica creada previamente (`PriceCategory`)
- Aplicar modelos de **regresión SVR** para estimar el `SalePrice`
- Comparar el desempeño de SVM con modelos de entregas anteriores (Árboles, Random Forest, Naive Bayes, KNN, Regresión Lineal)
- Afinar hiperparámetros (`kernel`, `C`, `gamma`, `degree`) para mejorar precisión
- Evaluar desempeño usando métricas y matrices de confusión
- Detectar y tratar sobreajuste o desajuste

---

#### Metodología

1. Reutilizar los conjuntos `train` y `test` usados en entregas previas
2. Preprocesar los datos para el uso con modelos SVM (normalización, codificación)
3. Entrenar modelos SVC y SVR con múltiples combinaciones de kernels y parámetros
4. Evaluar métricas como `accuracy`, `precision`, `recall`, `f1-score`, `RMSE`, `R²`
5. Comparar los mejores modelos de clasificación y regresión de SVM con los de entregas anteriores
6. Elaborar visualizaciones y tablas comparativas

---

#### Herramientas

- Python 3.x
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

---

#### Entregables

- Modelos de clasificación SVM (con y sin tuning)
- Modelos de regresión SVR (con y sin tuning)
- Comparación tabulada con modelos previos
- Análisis de errores y eficiencia
- Informe de resultados y conclusiones

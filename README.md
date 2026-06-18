# CanCalatrava - Predictive Modeling & Data Analysis

Este repositorio contiene el desarrollo de un proyecto de análisis de datos y modelado predictivo basado en un conjunto de datos competitivo. El objetivo principal es limpiar, explorar y predecir una variable objetivo (`deseada`) a partir de una serie de características numéricas que presentan valores ausentes y anomalías.

## 🚀 Contenido del Proyecto

El proyecto está dividido en dos notebooks principales de Jupyter:

1. **`CanCalatrava_DataAnalisis.ipynb`**:
* **Análisis Exploratorio de Datos (EDA):** Inspección inicial de las variables (`V0` a `V9`), estadísticas descriptivas y búsqueda de duplicados.
* **Preprocesamiento:** Tratamiento de valores nulos mediante técnicas de imputación avanzada como **KNN Imputer**.
* **Evaluación de Características:** Análisis de correlación e importancia de variables utilizando modelos basados en árboles.


2. **`CanCalatrava_modeltrain_test.ipynb`**:
* **Ingeniería de Variables:** Inyección de hiper-variables y selección automatizada de características (*feature selection*) eliminando variables irrelevantes.
* **Modelado Predictivo:** Configuración y entrenamiento de un flujo de trabajo de Machine Learning utilizando algoritmos robustos como **RandomForestRegressor**.
* **Ensemble Learning:** Implementación de un modelo combinado (**VotingRegressor**) y evaluación de métricas de rendimiento ($R^2$, MAE, RMSE).
* **Predicción y Exportación:** Pipeline final para generar predicciones sobre nuevos datos y exportar los resultados a formatos `.csv` y `.xlsx`.



## 🛠️ Tecnologías Utilizadas

* **Lenguaje:** Python 3
* **Manipulación de Datos:** `pandas`, `numpy`, `openpyxl`
* **Visualización:** `matplotlib`, `seaborn`, `plotly`
* **Machine Learning:** `scikit-learn` (Pipeline, StandardScaler, KNNImputer, RandomForest)
* **Modelos Avanzados:** `xgboost`, `catboost`
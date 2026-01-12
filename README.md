# Titanic Survival Prediction 🛳️

Proyecto de **Machine Learning** en Python basado en el clásico dataset del **Titanic (Kaggle)**, cuyo objetivo es predecir la supervivencia de los pasajeros utilizando **Regresión Logística**.

Este ejercicio cubre todo el flujo habitual de un proyecto de análisis de datos: limpieza, exploración, visualización y modelado.

---

## 📌 Objetivo del proyecto

Construir un modelo de **clasificación binaria** capaz de predecir si un pasajero sobrevivió o no al hundimiento del Titanic, a partir de variables demográficas y socioeconómicas.

---

## 📊 Dataset

- Fuente: **Kaggle – Titanic: Machine Learning from Disaster**
- Archivos utilizados:
  - `train.csv`
  - `test.csv`

El dataset ya viene separado en conjuntos de entrenamiento y test, lo que facilita el flujo de trabajo y la evaluación del modelo.

---

## 🔍 Análisis exploratorio de datos (EDA)

Antes de entrenar el modelo, se realiza un análisis exploratorio para comprender mejor los datos:

- Identificación de valores nulos
- Análisis de variables clave como:
  - Sexo
  - Clase del pasajero
  - Edad
  - Tarifa
- Visualización de la supervivencia en función de distintas variables mediante gráficos

Esto permite detectar patrones relevantes y tomar decisiones informadas para el preprocesado.

---

## 🧹 Limpieza y preprocesado de datos

Las principales tareas realizadas fueron:

- **Tratamiento de valores nulos**:
  - Variables numéricas completadas con la **media**
  - Variables categóricas completadas con la **moda**
- **Eliminación de columnas** que no aportan valor predictivo al modelo
- Codificación de variables categóricas
- Preparación final del dataset para el entrenamiento del modelo

---

## 🤖 Modelado

Se utiliza un modelo de **Regresión Logística**, adecuado para problemas de clasificación binaria y fácilmente interpretable.

- Librerías principales:
  - `pandas`
  - `numpy`
  - `matplotlib` / `seaborn`
  - `scikit-learn`
- Entrenamiento del modelo sobre el conjunto `train`
- Evaluación del rendimiento mediante **accuracy**

---

## ✅ Resultados

- **Accuracy obtenido:** **0.93**

Este resultado indica un alto nivel de precisión en la predicción de supervivencia, demostrando la efectividad del preprocesado y la selección de variables.

---

🚀 Conclusiones

Este proyecto demuestra cómo un buen análisis exploratorio y una correcta preparación de los datos pueden tener un impacto directo en el rendimiento de un modelo de Machine Learning, incluso utilizando algoritmos clásicos como la Regresión Logística.

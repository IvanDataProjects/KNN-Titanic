# Predicción de Supervivencia en el Titanic con KNN 🚢

## 📌 Descripción del Proyecto
Este proyecto utiliza el dataset del Titanic para predecir la supervivencia de los pasajeros mediante el algoritmo **K-Nearest Neighbors (KNN)**. El objetivo es predecir si un pasajero sobrevivió o no al hundimiento del Titanic en función de sus características (edad, sexo, clase, etc.).

El trabajo se divide en dos fases principales:

1. **Exploración y limpieza del dataset**.
2. **Entrenamiento y evaluación del modelo de clasificación** utilizando KNN.

---

## 🎯 Objetivo
El objetivo principal es desarrollar un modelo de clasificación para:
- Predecir la probabilidad de supervivencia de los pasajeros.
- Evaluar el rendimiento del modelo utilizando métricas como precisión, matriz de confusión y clasificación.

---

## 🧹 Parte 1: Limpieza y preparación de datos

Antes de entrenar el modelo, es esencial realizar una limpieza y preparación del dataset:

- **Análisis de columnas**: Identificar variables relevantes.
- **Tratamiento de valores nulos**: Verificar y gestionar datos faltantes.
- **Codificación de variables**: Convertir variables categóricas en numéricas.
- **Escalado de variables numéricas**: Asegurar que las características numéricas estén en un rango similar.
- **División de datos**: Separar en entrenamiento y prueba.

Una vez limpio, el dataset se encuentra listo para ser utilizado en el modelo.

---

## 📊 Parte 2: Entrenamiento y evaluación del modelo

Se utiliza el algoritmo **K-Nearest Neighbors (KNN)** para predecir la supervivencia de los pasajeros:

### 🔎 Evaluación del modelo
- **Entrenamiento del modelo**: Ajustar el modelo a los datos de entrenamiento.
- **Métricas de evaluación**: Usar métricas como **accuracy**, **matriz de confusión**, etc.
- **Predicciones**: Realizar predicciones sobre el conjunto de test.
- **Precisión (Accuracy)**: El modelo alcanzó una precisión de **0.6866028708133971**.

---

## 📁 Archivos incluidos
- `titanic_knn.ipynb`: Jupyter notebook con todo el proceso de limpieza, análisis y modelado.
- `train.csv`: Dataset de entrenamiento.
- `test.csv`: Dataset de prueba para hacer las predicciones.

---

## 🛠️ Tecnologías utilizadas
- Python (Pandas, Matplotlib, Scikit-learn, seaborn, numpy, neighbors, confusion_matrix, accuracy_score)
- Jupyter Notebook

---

## 🚀 Autor
Iván García Raso  
[GitHub - IvanMLProjects](https://github.com/IvanMLProjects)  
[LinkedIn](https://www.linkedin.com/in/ivan-garcia-raso)

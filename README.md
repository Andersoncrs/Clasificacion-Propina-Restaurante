# **Predicción de Propinas en un Restaurante**
![](https://raw.githubusercontent.com/Andersoncrs/Clasificacion-Propina-Restaurante/refs/heads/main/Modelos_Clasificacion.png)

¡Bienvenido al proyecto de análisis y modelado de propinas! Aquí encontrarás todo lo necesario para entender cómo predecimos si un cliente dejará propina basándonos en sus características.

Este informe explora el famoso dataset *tips* y sigue un paso a paso desde la carga de datos hasta la comparación de dos modelos de clasificación:

1. **Support Vector Machines (SVM)**
2. **Regresión Logística**

El objetivo es descubrir patrones en el comportamiento de los clientes y cuantificar qué tan bien cada enfoque predice la propina.

---

## 🔍 Metodología

1. **Ingesta de datos**: Cargamos el dataset `tips` de seaborn.
2. **Análisis Exploratorio (EDA)**:

   * Estadísticos descriptivos.
   * Detección y eliminación de duplicados.
   * Categorización de la variable objetivo (¿propina o no?).
   * Mapeo de variables cualitativas a valores numéricos.
3. **Preparación**:

   * División en conjuntos de entrenamiento y prueba.
4. **Modelado**:

   * Entrenamos y evaluamos un modelo SVM.
   * Entrenamos y evaluamos una regresión logística.
5. **Comparación de resultados**:

   * Métricas de precisión, recall y F1.

---

## 💡 Conocimientos Aplicados

* **Python & pandas**: para manipulación y limpieza de datos.
* **EDA**: identificación de patrones y outliers.
* **Codificación de variables**: transformación de datos categóricos.
* **scikit-learn**: entrenamiento y evaluación de modelos de clasificación.
* **SVM**: teoría básica y ajustes de hiperparámetros.
* **Regresión Logística**: interpretación de coeficientes y métricas de clasificación.
* ## 💡 Conocimientos Aplicados

* **Python & pandas**: para manipulación y limpieza de datos.
* **EDA**: identificación de patrones y outliers.
* **Codificación de variables**: transformación de datos categóricos.
* **scikit-learn**: entrenamiento y evaluación de modelos de clasificación.
* **SVM**: teoría básica y ajustes de hiperparámetros.
* **Regresión Logística**: interpretación de coeficientes y métricas de clasificación.
* **Análisis de resultados**
---

## 📝 Conclusiones

El informe muestra cómo con unos cuantos pasos sencillos de limpieza y modelado, podemos construir predictores que nos ayuden a entender mejor las propinas. Cada modelo tiene sus pros y sus contras, y la elección final dependerá de qué tan importante sea maximizar la precisión versus la interpretabilidad.

---


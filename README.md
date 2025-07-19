# TelecomX_2

# 📊 Predicción de Cancelación de Clientes (Churn)

Este proyecto utiliza técnicas de aprendizaje automático para predecir la cancelación de clientes en una empresa de telecomunicaciones, a partir de un dataset con información demográfica, contractual y de consumo.

---

## 🧠 Modelos aplicados

- 🔹 Regresión Logística (con datos normalizados)
- 🔹 Random Forest (sin normalización)

---

## ⚙️ Herramientas utilizadas

- Google Colab (Python)
- Pandas y NumPy (manipulación de datos)
- Seaborn y Matplotlib (visualización)
- Scikit-learn (modelado y métricas)
- imbalanced-learn (SMOTE para balanceo de clases)

---

## 🔍 Proceso

1. **Carga y limpieza de datos**
   - Eliminación de valores nulos y columnas irrelevantes (como `customerID`)
   - Desanidado de columnas con diccionarios (ej. `internet`, `account`)
   - Conversión de variables categóricas a numéricas (One-Hot Encoding)

2. **Análisis exploratorio**
   - Visualización de correlaciones
   - Boxplots y análisis de variables más influyentes (tenure, gastos, métodos de pago)

3. **Modelado**
   - División en set de entrenamiento/prueba (80/20)
   - Aplicación de SMOTE para balancear clases
   - Entrenamiento con Regresión Logística y Random Forest

4. **Evaluación**
   - Métricas: Accuracy, Precision, Recall, F1-score
   - Matrices de confusión
   - Importancia de variables

---

## 🧾 Resultados principales

| Modelo              | Accuracy | Precision | Recall | F1 Score |
|---------------------|----------|-----------|--------|----------|
| Regresión Logística | 0.82     | 0.67      | 0.54   | 0.60     |
| Random Forest       | 0.79     | 0.58      | 0.61   | 0.59     |

---

## 🧠 Principales variables que predicen el Churn

- account_Charges_Total
- customer_tenure
- account_Charges_Monthly
- account_PaymentMethod_Electronic check
- account_PaperlessBilling_Yes
- internet_InternetService_Fiber optic

---

## 💡 Estrategias propuestas de retención

- Incentivar contratos de mayor duración
- Detectar clientes con altos gastos mensuales o totales
- Intervenir preventivamente en clientes con métodos de pago electrónicos
- Mejorar la experiencia de clientes con servicios de fibra óptica

---

## 🗂️ Archivos

- `notebook.ipynb`: Notebook principal con todo el proceso
- `json_limpio.json`: Dataset ya preprocesado y limpio

---

## 📬 Contacto



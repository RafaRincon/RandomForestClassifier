# 🔍 Clasificación Supervisada con ML sobre `info_02.csv`

Este proyecto tiene como objetivo entrenar y comparar modelos de **machine learning supervisado** para predecir etiquetas en el dataset `info_02.csv`. Se emplean diversas técnicas de análisis exploratorio, preparación de datos y validación para garantizar resultados precisos y confiables.

---

## 🎯 Objetivo

Entrenar modelos de clasificación supervisada capaces de predecir etiquetas en el dataset `info_02.csv`, evaluando su desempeño y capacidad de generalización.

---

## 🧰 Tecnologías y Herramientas

- **Entorno:** Anaconda (Jupyter Notebook en Windows)
- **Lenguaje:** Python 3.12.7
- **Librerías utilizadas:**
  - `scikit-learn` – Modelado y métricas
  - `pandas` – Manipulación de datos
  - `matplotlib` & `seaborn` – Visualización de datos
  - `xgboost` – Gradient Boosting

---

## 🧪 Metodología

### 1. Análisis Exploratorio de Datos (EDA)
- 🔁 Detección y eliminación de valores duplicados
- 🚫 Detección de valores nulos
- 🧹 Limpieza y eliminación de outliers
- 🔍 Análisis de correlación con matriz de Pearson
- 🧩 Imputación de valores faltantes

### 2. Análisis de Balance de Clases
- Evaluación del desbalance en las clases objetivo
- Consideración de técnicas de remuestreo si es necesario (e.g., SMOTE)

### 3. Modelado y Comparación
- Entrenamiento de los siguientes modelos:
  - `Random Forest`
  - `SVM (Support Vector Machine)`
  - `XGBoost`
- Comparación de desempeño usando métricas clave (precisión, recall, F1-score)

### 4. Validación Cruzada
- Aplicación de **k-fold cross-validation** para evaluar la robustez de los modelos y detectar posibles problemas de **overfitting**

---

## 📈 Resultados Esperados

Comparación clara entre modelos en términos de:
- Desempeño en entrenamiento vs validación
- Sensibilidad al desbalance de clases
- Interpretabilidad y tiempos de entrenamiento

---

## 🚀 Cómo ejecutar el proyecto

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tuusuario/tu-repo.git
   ```
2. Abre el proyecto con Anaconda Navigator o Jupyter Notebook.
3. Asegúrate de tener las dependencias instaladas:
   ```bash
   pip install -r requirements.txt
   ```
4. Ejecuta el notebook principal: `modelo_clasificacion.ipynb`

---

## 📁 Estructura del proyecto

```
├── data/
│   └── info_02.csv
├── notebooks/
│   └── modelo_clasificacion.ipynb
├── models/
│   ├── random_forest_model.pkl
│   ├── SVM_model.pkl
│   └── XGBoost_model.pkl
├── results/
│   └── graficos_comparativos.png
├── README.md
└── requirements.txt
```

# Challenge_Telecom_X_pt2
Challenge Telecom X: análisis de evasión de clientes - Parte 2

**Telecom X – Predicción de Cancelación de Clientes (Churn)**
**Descripción**

Este proyecto forma parte del desafío Telecom X – Parte 2 y tiene como objetivo desarrollar modelos predictivos capaces de identificar clientes con mayor probabilidad de cancelar el servicio (churn).

A partir de un dataset previamente tratado, se realiza un proceso de preparación de datos, análisis exploratorio y entrenamiento de modelos de machine learning para comprender qué factores influyen en la cancelación de clientes.

**Estructura del proyecto**
TelecomX-Churn-Prediction
│
├── TelecomX_Modelos_Predictivos.ipynb   # Notebook principal
├── TelecomX_tratado.csv                 # Dataset limpio
└── README.md                            # Documentación del proyecto

**Preparación de los datos**

Antes de entrenar los modelos se realizaron varias etapas de preparación de datos:

Clasificación de variables en categóricas y numéricas

Codificación de variables categóricas mediante One-Hot Encoding

Revisión de valores faltantes

Separación del dataset en datos de entrenamiento (70%) y prueba (30%)

Estas etapas permiten preparar los datos para el entrenamiento de modelos predictivos.

**Modelos utilizados**

Se implementaron dos modelos de clasificación:

Regresión Logística

Árbol de Decisión

Estos modelos permiten predecir la cancelación de clientes y comparar su desempeño.

**Evaluación de modelos**

El desempeño de los modelos se evaluó utilizando métricas de clasificación como:

Accuracy

Precision

Recall

F1-score

Matriz de confusión

Esto permitió analizar qué modelo logra predecir de manera más efectiva la cancelación de clientes.

**Análisis Exploratorio de Datos (EDA)**

Durante el análisis exploratorio se generaron visualizaciones para comprender el comportamiento de los clientes, incluyendo:

Distribución de la variable Churn

Análisis de correlación entre variables

Boxplots para analizar la relación entre tenure, gasto total y cancelación

Estos análisis permitieron identificar patrones importantes en el comportamiento de los clientes.

**Principales insights**

Algunos factores que influyen en la cancelación de clientes son:

Tiempo de permanencia del cliente (tenure)

Cargos mensuales y gasto total

Tipo de servicio contratado

Estos resultados pueden ayudar a la empresa a identificar clientes con mayor riesgo de cancelación.

**Cómo ejecutar el proyecto**

El proyecto puede ejecutarse en Google Colab.

Librerías necesarias
pandas
numpy
matplotlib
seaborn
scikit-learn
Pasos para ejecutar

Abrir el notebook TelecomX_Modelos_Predictivos.ipynb.

Cargar el archivo TelecomX_tratado.csv.

Ejecutar las celdas en orden para reproducir el análisis.

# Telecom-X-Parte-2

Telecom X – Predicción de Cancelación de Clientes (Churn) – Parte 2
Historia del Desafío

Después de completar con éxito el análisis exploratorio de la evasión de clientes en Telecom X, fui invitado a formar parte del equipo de Machine Learning de la empresa. La misión ahora es desarrollar modelos predictivos que permitan identificar qué clientes tienen mayor probabilidad de cancelar sus servicios, anticipándose al problema de Churn y ofreciendo a la empresa herramientas para tomar decisiones estratégicas.

Objetivo del Proyecto

Construir un pipeline de Machine Learning capaz de:

Preparar los datos (limpieza, codificación y normalización) para su uso en modelos predictivos.

Analizar la correlación entre variables y seleccionar las más relevantes.

Entrenar dos o más modelos de clasificación para predecir la cancelación de clientes.

Evaluar el desempeño de los modelos mediante métricas como exactitud, precisión, recall y F1-score.

Interpretar los resultados, destacando las variables que más impactan la predicción de Churn.

Generar insights estratégicos que permitan a Telecom X reducir la tasa de cancelación.

Metodología

Preprocesamiento de datos

Eliminación de columnas irrelevantes y duplicadas.

Transformación de variables categóricas a formato numérico (One-Hot Encoding).

Normalización de variables numéricas para modelos sensibles a escala.

Análisis exploratorio y correlación

Visualización de relaciones entre variables numéricas y categóricas con Churn.

Selección de características relevantes para el modelado.

Entrenamiento de modelos

Se entrenaron modelos como Regresión Logística y Random Forest, evaluando la necesidad de normalización según el algoritmo.

Validación del rendimiento en conjunto de prueba y análisis de overfitting/underfitting.

Interpretación de variables

Identificación de los factores que más influyen en la cancelación de clientes, usando coeficientes, importancia de variables y análisis de proximidad.

Conclusiones estratégicas

Se elaboraron recomendaciones basadas en los hallazgos para reducir el Churn y mejorar la retención de clientes.

Principales Aprendizajes

Modelos basados en árboles (Random Forest) capturan relaciones no lineales y muestran un rendimiento robusto incluso sin normalización.

Regresión Logística permite interpretar el impacto de cada variable en la probabilidad de cancelación.

Variables como tiempo de contrato, gasto total y servicios adicionales son determinantes para predecir Churn.

La combinación de análisis exploratorio, preprocesamiento y modelado predictivo permite generar insights accionables para estrategias de retención.

Tecnologías Utilizadas

Python

Pandas & NumPy

Scikit-Learn

Matplotlib & Seaborn

Jupyter Notebook

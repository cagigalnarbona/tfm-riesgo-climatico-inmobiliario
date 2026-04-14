# Riesgo climático en la tasación inmobiliaria  
## Un enfoque geoespacial con simulación

## Descripción

Este proyecto analiza el impacto del cambio climático en el precio de la vivienda en España mediante un enfoque geoespacial y modelos predictivos.

Se integran variables climáticas (temperatura y precipitaciones), datos macroeconómicos y datos inmobiliarios para evaluar su influencia sobre el precio por metro cuadrado.

---

## Objetivo

Evaluar si el riesgo climático tiene un impacto significativo en la valoración inmobiliaria y mejorar la capacidad predictiva mediante modelos de series temporales y machine learning.

---

## Datos utilizados

El proyecto combina cuatro fuentes principales:

- Tasaciones oficiales del Ministerio de Vivienda (1995–2025)  
- Series macroeconómicas del Banco de España  
- Datos climáticos históricos y proyectados (CMIP6)  
- Dataset inmobiliario georreferenciado con más de 180.000 inmuebles  

---

## Metodología

### Preparación de datos
- Limpieza y transformación de datasets  
- Unificación espacio-temporal  
- Creación de variables (lags, diferencias y variables climáticas)  

### Análisis exploratorio
- Evolución del precio de la vivienda  
- Distribución de variables  
- Análisis climático (temperatura y precipitaciones)  
- Visualización geoespacial  

### Modelización

Modelos econométricos:
- SARIMA  
- SARIMAX  

Modelos de machine learning:
- Random Forest  
- LightGBM  
- XGBoost  
- AdaBoost  

Deep learning:
- Redes neuronales LSTM  

### Evaluación
- RMSE  
- MAE  
- R²  
- Validación fuera de muestra  

---

## Resultados

- Las variables macroeconómicas explican la mayor parte del comportamiento del precio  
- Las variables climáticas presentan efectos incipientes y heterogéneos según la región  
- Los modelos lineales presentan limitaciones en la capacidad predictiva  
- Los modelos no lineales capturan mejor patrones complejos en determinadas zonas  

---

## Conclusiones

El riesgo climático comienza a influir en el mercado inmobiliario, aunque su impacto es todavía limitado frente a los factores económicos.

El proyecto propone un marco metodológico replicable para integrar escenarios climáticos en modelos de valoración inmobiliaria.

---

## Aplicaciones

- Evaluación de riesgo en entidades financieras  
- Toma de decisiones en inversión inmobiliaria  
- Planificación urbana  
- Modelización de riesgo climático  

---

## Tecnologías

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Statsmodels  
- XGBoost, LightGBM  
- TensorFlow / Keras  
- Matplotlib  

---

## Estructura del proyecto

data/ → datos originales y procesados  
notebooks/ → análisis y modelización  
src/ → código modular  
models/ → modelos entrenados y métricas  
reports/ → memoria del TFM  
images/ → gráficos y visualizaciones  

---

## Autor

Eduardo Cagigal Narbona  
Máster en Big Data & Data Science – Universidad de Barcelona

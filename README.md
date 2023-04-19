# Análisis de exploración y modelado de Machine Learning

Este repositorio contiene el código y los recursos utilizados para realizar un análisis de exploración y modelado de Machine Learning en un conjunto de datos de comercio electrónico. Se han utilizado diversas herramientas y técnicas, incluyendo una canalización de datos en Google Cloud Platform (GCP) Data Fusion, Jupyter Notebooks, y Looker Studio para la presentación de resultados.

## Índice

1. [Canalización de datos en GCP Data Fusion](#canalizacion)
2. [Análisis exploratorio y estadístico](#analisis)
3. [Entrenamiento de modelos de Machine Learning](#modelado)
4. [Informe en Looker Studio](#looker)

<a name="canalizacion"></a>

## 1. Canalización de datos en GCP Data Fusion

Se implementó una canalización en Data Fusion de GCP para simular una integración semanal de datos como si fuese una API. El script para esta canalización se encuentra en el siguiente directorio del repositorio:

/src/pepeline/Pepiline_ecomm-cdap-data-pipeline.json

Este scrip se importa en Data Fusión y se ejecuta de forma semanal.

<a name="analisis"></a>

## 2. Análisis exploratorio y estadístico

Se desarrolló un Jupyter Notebook para consumir la canalización de datos desde una tabla de BigQuery, importar los datos transformados, realizar el análisis exploratorio y estadístico, y luego correlacionar las variables con la variable objetivo. El Notebook se encuentra en el siguiente enlace:

/notebooks/analisis.ipynb

<a name="modelado"></a>

## 3. Entrenamiento de modelos de Machine Learning

Se creó otro Jupyter Notebook para entrenar los modelos, verificar su rendimiento y armar las consultas para enviar a predecir los resultados de los modelos entrenados. Se entrenaron dos modelos, uno de clasificación y otro de clustering. El Notebook se encuentra en el siguiente enlace:

/notebooks/entrenamiento.ipynb

<a name="looker"></a>

## 4. Informe en Looker Studio

Se preparó un informe en Looker Studio para realizar la presentación de la investigación, conectado a BigQuery completamente automatizado. El informe está disponible en el siguiente enlace:

https://lookerstudio.google.com/reporting/ff7fc397-c4f8-4327-a635-033929d09282

## Autores

Nicolas Ferreyra Calarco

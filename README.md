# Análisis de Sentimientos de Noticias Financieras

Este repositorio contiene un proyecto de análisis de sentimientos aplicado a un conjunto de datos de noticias financieras. El objetivo principal es clasificar las noticias en diferentes categorías y analizar el sentimiento asociado a cada una.

## Contenido del Repositorio

- **Notebooks de Jupyter (`.ipynb`):** Contienen el código del pipeline de análisis de datos, desde el pre-procesamiento hasta la modelización y análisis de sentimientos.
- **`archivos/`:** Almacena los datasets generados durante las fases del proyecto, así como el modelo `doc2vec` entrenado.
- **`plots/`:** Contiene las visualizaciones y gráficos generados a partir del análisis, como nubes de palabras y métricas de modelos.
- **`recursos/`:** Incluye los recursos iniciales para el análisis, como el dataset original (`news.csv`), diccionarios de palabras y palabras clave.

## Pipeline de Análisis de Datos

El proyecto se desarrolla a través de los siguientes pasos, cada uno implementado en su respectivo notebook:

1.  **`0_análisis_del_dataset.ipynb`:** Análisis exploratorio inicial del conjunto de datos.
2.  **`1_pre-procesamiento.ipynb`:** Limpieza y pre-procesamiento del texto de las noticias.
3.  **`2_balanceo-clases.ipynb`:** Balanceo de las clases del dataset para mejorar el rendimiento de los modelos.
4.  **`3_practica_pca.ipynb`:** Aplicación de PCA (Análisis de Componentes Principales) para la reducción de dimensionalidad.
5.  **`4_agregar_covariables.ipynb`:** Incorporación de covariables para enriquecer el análisis.
6.  **`5_analizador_de_sentimientos.ipynb`:** Desarrollo y aplicación del analizador de sentimientos.

## Resultados

Los resultados del análisis, incluyendo las métricas de los modelos y las visualizaciones, se pueden encontrar en la carpeta `plots/`. Estos gráficos ayudan a interpretar los datos y los resultados del análisis de sentimientos.

## Cómo Utilizar

Para replicar el análisis, se recomienda ejecutar los notebooks en el orden numérico establecido, ya que siguen una secuencia lógica y dependen de los archivos generados en los pasos anteriores.

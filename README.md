# Análisis de Opinión en Repositorios Git

Este proyecto aplica técnicas de Procesamiento de Lenguaje Natural (PLN) para analizar la "salud" de un proyecto de software open source (scikit-learn) mediante el análisis de issues, pull requests y comentarios.

## Autores
**Universidad de Guayaquil - Facultad de Ciencias Matemáticas y Físicas**
* Alcivar Macay Anthony Yandry
* Quintana Pluas Luis Alejandro
* Rodriguez Bautista Juren David

**Asignatura:** Procesamiento del Lenguaje Natural
**Docente:** Ing. Angel Cuenca Ortega

## Estructura del Repositorio

* **`data/`**: Contiene el dataset `datos_github.csv` recolectado a través de la API de GitHub.
* **`src/`**: Contiene el código fuente (`.ipynb`) con la implementación de:
    * Recolección de datos.
    * Preprocesamiento (limpieza, stemming, eliminación de stopwords).
    * Representación TF-IDF.
    * Análisis de Sentimiento (VADER).
    * Modelado de Tópicos (K-Means).
    * Similitud de Coseno.

## Instrucciones de Ejecución
Si desea ejecutar la recolección de datos desde cero, por favor inserte su propio Personal Access Token en la variable token_github dentro del notebook
### Requisitos Previos
El proyecto fue desarrollado en Python. Las librerías necesarias se encuentran en `requirements.txt`. Puedes instalarlas ejecutando:

```bash
pip install -r requirements.txt


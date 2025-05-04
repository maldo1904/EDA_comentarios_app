# Análisis Exploratorio de Datos (EDA) sobre Comentarios de una Aplicación

Este repositorio contiene el análisis exploratorio de datos (EDA) de los comentarios de una aplicación. El objetivo de este análisis es explorar diferentes características de los datos y generar visualizaciones para entender patrones, tendencias y relaciones entre las variables.

## Descripción

En este proyecto, se analizaron varias columnas del dataset, como la calificación, el director, el elenco, el país y la fecha de adición de los títulos. También se analizó la duración de los títulos y su relación con otras variables. Se llevaron a cabo las siguientes tareas:

- **Limpieza de datos**: Se gestionaron valores nulos y se hicieron correcciones en los datos.
- **Análisis de la duración de los títulos**: Se identificaron los títulos con mayor duración y la duración promedio por año.
- **Distribución de las calificaciones**: Se analizaron las clasificaciones (ratings) más comunes en los datos.
- **Análisis de los géneros**: Se desglosaron los géneros más frecuentes, observando tendencias como la prevalencia de "International Movies".
- **Evolución de la duración de los títulos**: Se exploró cómo ha cambiado la duración promedio de los títulos a lo largo de los años.

## Tecnologías Utilizadas

- **Python**
  - Pandas
  - Matplotlib
  - Seaborn

## Resultados

- Se observó una fuerte tendencia al aumento en el número de títulos lanzados en los años más recientes.
- Los géneros más populares incluyen *International Movies*, mientras que los *TV shows* son los menos vistos.
- Las clasificaciones más comunes son *TV-MA* y *TV-14*.
- La duración de los títulos varió significativamente a lo largo de los años, con una tendencia a títulos más cortos en tiempos recientes.

## Requisitos

- Python 3.x
- Las librerías necesarias están listadas en el archivo `requirements.txt`:

```txt
pandas
matplotlib
seaborn

# Proyecto de Análisis de Datos de Libros

Este proyecto realiza un proceso de **ETL (Extracción, Transformación y Carga)** y **Análisis Exploratorio de Datos (EDA)** sobre un conjunto de datos de libros, finalizando con una **visualización interactiva en Power BI** que permite explorar las calificaciones, categorías, autores y otras métricas clave de los libros.

## Enlace al Dashboard Interactivo en Power BI

Puedes acceder al dashboard interactivo aquí: [Dashboard de Análisis de Libros en Power BI](https://app.powerbi.com/view?r=eyJrIjoiMmQ4ZTE5NTktNDNhMy00N2M0LThlNDEtYmQzZmY5ZDhhZjVhIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9)

## Descripción del Proyecto

### 1. Extracción de Datos
- Se utilizó un archivo CSV llamado **book.csv** que contiene información sobre libros, como título, autor, categorías, calificación promedio, número de calificaciones y año de publicación.

### 2. Proceso de ETL
- **Extracción**: Se cargaron los datos desde el CSV al entorno de trabajo en Python.
- **Transformación**: Se limpiaron y prepararon los datos, eliminando valores nulos y ajustando formatos para columnas específicas, como la fecha y las listas de categorías.
- **Carga**: Los datos limpios se guardaron en un nuevo archivo CSV llamado **books_clean.csv** para ser utilizados en el análisis y visualización.

### 3. Análisis Exploratorio de Datos (EDA)
Durante el EDA, se realizaron las siguientes preguntas para obtener información valiosa:
- Distribución de calificaciones promedio y la relación entre el año de publicación y la popularidad de los libros.
- Análisis de las categorías más populares y los autores más calificados.
- Identificación de tendencias en calificaciones a lo largo del tiempo y correlaciones entre variables clave (calificación promedio, número de calificaciones y año).

### 4. Visualización en Power BI
Con los datos procesados, se creó un dashboard interactivo en Power BI que incluye visualizaciones de:
- **Categorías más votadas** y distribución de calificaciones por categoría.
- **Autores más exitosos** basados en la cantidad de calificaciones.
- **Tendencias de calificaciones** por año de publicación.
- **Relaciones entre variables** como calificaciones promedio y número de reseñas.

## Herramientas Utilizadas
- **Python**: para el procesamiento de datos y el EDA.
- **Pandas**: para la manipulación de datos.
- **Power BI**: para la creación del dashboard interactivo.

## Instrucciones para Reproducción

1. Clona este repositorio y asegúrate de tener instalado Python y las librerías requeridas.
2. Ejecuta el archivo de procesamiento de datos para limpiar y preparar el CSV.
3. Importa el archivo **books_clean.csv** en Power BI y replica el dashboard utilizando los mismos campos visualizados en el enlace.

## Conclusiones
Este proyecto proporciona una visión integral de los datos de libros, destacando tendencias y relaciones importantes que ayudan a comprender mejor las preferencias de los lectores y el rendimiento de los libros en diferentes categorías.

## Desarrollador de este proyecto de MLops.
[<img src="https://avatars.githubusercontent.com/u/117546891?s=400&u=6a6327d1cbf13545fd79dbb73d8193b5b01e5548&v=4" width=115><br><sub>Pedro Oria</sub>](https://github.com/pedroOria)

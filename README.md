# Proyecto MLOps para Steam

## Introducción

Este proyecto simula el rol de un Ingeniero MLOps para la plataforma de videojuegos Steam. Se busca desarrollar un Producto Mínimo Viable (MVP) que incluya la implementación de una API en la nube y la aplicación de dos modelos de machine learning para análisis de sentimientos en los comentarios de usuarios y recomendación de juegos.

## Contexto

Steam, desarrollado por Valve Corporation, es una plataforma de distribución digital de videojuegos con una vasta base de usuarios y una amplia selección de juegos, y nos pide aplicar , entre otras cosas, un modelo de recomendacion de juegos.

## Datos

Se trabajó con tres conjuntos de datos JSON que incluían comentarios de usuarios sobre juegos, información sobre juegos jugados por usuarios y detalles de los juegos en sí.

## Tareas de transformacion Realizadas

Se realizaron operaciones de extracción, transformación y carga (ETL) en los tres conjuntos de datos utilizando Pandas.
Se procesaron conjuntos de datos anidados aplicando diversas estrategias para transformar las claves de los diccionarios en columnas.
Se completaron los valores nulos en variables esenciales y se eliminaron columnas sin relevancia para el proyecto para optimizar el rendimiento de la API y considerar las limitaciones de almacenamiento en el despliegue.

### Transformaciones

- Se realizaron operaciones de ETL en los conjuntos de datos para adecuarlos al análisis.
- Se completaron valores nulos y se eliminaron columnas innecesarias para optimizar el rendimiento de la API.

### Ingeniería de Características

- Se aplicó análisis de sentimientos a los comentarios de usuarios, generando una nueva columna.
- Se utilizó TextBlob para realizar un análisis básico de sentimientos.

### Análisis Exploratorio de Datos (EDA)

- Se realizó un EDA para identificar variables relevantes para el modelo de recomendación.

### Modelo de Aprendizaje Automático

- Se desarrollaron dos modelos de recomendación: item-item y user-item.
- Se utilizó la similitud del coseno para medir la similitud entre juegos y usuarios.
- Se crearon funciones de API para recomendar juegos.

### Desarrollo de la API

- Se implementó una API utilizando FastAPI para permitir consultas sobre datos de usuario, análisis de desarrolladores, entre otros.

## Oportunidades de Mejora

Se identificaron áreas de mejora, como la limpieza de comentarios, la incorporación de factores adicionales en los modelos de recomendación y un EDA más exhaustivo.

## Ejecución de la API Localmente

Para ejecutar la API localmente, siga los pasos en el archivo README.md.

## Criterios de Evaluación

Se evaluó la organización del código, el cumplimiento de los requisitos del proyecto y la presentación clara en el README.md.

## Presentación en Video

Se realizó una presentación en video demostrando las funcionalidades de la API y explicando el modelo de recomendación.

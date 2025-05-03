# Canalización ETL sin servidor con API de OpenWeather y AWS S3

## Introducción

Este proyecto demuestra una canalización ETL (Extracción, Transformación y Carga) ligera que utiliza Python y tecnologías en la nube. El script obtiene datos meteorológicos en tiempo real de la API de OpenWeatherMap, los procesa para extraer métricas clave y carga los resultados en un bucket de AWS S3 en formato JSON.

Está diseñado para implementarse en un entorno de funciones en la nube (p. ej., AWS Lambda), lo que demuestra habilidades clave en integración de API, almacenamiento en la nube y gestión de errores.

## Tecnologías usadas

- Amazaron S3
- Python
- Dotenv

## ETL Flow

- Extraer: Obtener datos meteorológicos para una ciudad específica
- Transformación: Analizar y formatear atributos meteorológicos relevantes
- Carga: Sube el archivo JSON estructurado a un bucket de AWS S3 específico.



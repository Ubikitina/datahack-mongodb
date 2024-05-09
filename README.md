# Modelado y Gestión de Datos NoSQL

## Objetivo

Este proyecto implementa un caso de uso de modeloado y gestión de datos NoSQL utilizando el conjunto de datos de la Calidad del Aire de la ciudad de Madrid. Se busca aplicar los conocimientos en el modelado y gestión de datos NoSQL utilizando MongoDB como sistema de base de datos orientado a documentos. El proyecto ha sido realizado como parte del Máster Experto Big Data Architecture & Engineering en Datahack.

Tecnologías utilizadas:
- MongoDB
- Jupyter Notebook
- Docker
- Python
- Librerías de visualización de gráficos en Python: matplotlib

## Caso de Uso

El caso de uso implica el análisis y gestión de los datos de calidad del aire de Madrid. Se realizarán consultas, análisis y visualizaciones sobre estos datos para obtener información relevante sobre la calidad del aire en diferentes zonas y períodos de tiempo (series temporales).

## Requerimientos

Para la implementación de este proyecto, se requiere:

- MongoDB instalado y configurado.
- Jupyter Notebook para ejecutar el análisis de datos.

Ambos se pueden levantar utilizando Docker mediante el [docker-compose](docker-compose.yaml) adjunto.

### Cómo ejecutar
Accede a la carpeta raíz del proyecto y ejecuta:
```
$ docker-compose up -d
```

Para detener el entorno, ejecuta:
```
$ docker-compose down
```

## Implementación
La implementación se encuentra en el archivo [Practica.ipynb](Practica.ipynb). 

### Resumen
Se han analizado diferentes sistemas de bases de datos, incluyendo bases de datos relacionales y diferentes tipos de bases de datos NoSQL, evaluando su idoneidad para este proyecto.

La implementación del caso de uso se ha llevado a cabo utilizando MongoDB como sistema de base de datos NoSQL. Se han utilizado técnicas de modelado de datos orientadas a documentos para almacenar y gestionar la información de la calidad del aire. Como énfasis, se han implementado series temporales (time series) utilizando MongoDB. Además, se han desarrollado consultas y análisis sobre estos datos utilizando las funcionalidades proporcionadas por MongoDB y librerías de visualización de gráficos en Python.


### Estructura del archivo [Practica.ipynb](Practica.ipynb)

- Objetivo
- Caso de uso
  - Descripción de la fuente de datos
  - Descripción del caso de uso
- Análisis de los sistemas de bases de datos
  - Requerimientos
  - Bases de datos relacionales
  - Clave/Valor (NoSQL)
  - Familias de Columnas (NoSQL)
  - Documentos (NoSQL)
  - Colas de mensajes (NoSQL)
  - Grafos (NoSQL)
- Modelado de datos
  - Primera iteración
  - Segunda iteración
  - Diagrama de modelo de datos final
- Inserción de datos en el modelo
  - Fuentes de datos
  - Ingesta de datos
    - Importar los datos de las mediciones de la calidad de aire
    - Importar datos de las estaciones de medida

- Sentencias de consulta
  - Exploración general
  - Consultas para nuestro Caso de Uso
    - Consulta 1: Promedio de NO2 por mes en cada estación en el 2023
    - Consulta 2: Promedio de NO2 por día en una estación en el 2023
    - Consulta 3: Evolución del NO2 por hora durante una semana del 2023 en una estación

- Conclusiones
  - ¿Qué te parece la base de datos seleccionada como data store?
  - ¿Qué te ha parecido el ejercicio?
  - ¿Qué has aprendido?
  - ¿Qué has echado de menos?
  - ¿Cómo mejorarías la práctica?
  - Futuras líneas

- Bibliografía


# PROYECTO_FINAL
# Análisis Exploratorio de Ventas y Rentabilidad de una Cadena de Supermercados

## Descripción

El dataset **Sample - Superstore.csv** contiene contiene información histórica de ventas de una cadena de supermercados.  
Cada registro contiene información relacionada con:

- Pedidos
- Clientes
- Productos y subcategorías
- Categorías de productos
- Segmentos de clientes
- Regiones y estados
- Ventas
- Descuentos aplicados
- Ganancias obtenidas
- Cantidad de productos vendidos

## Objetivo

El objetivo principal es realizar un análisis exploratorio del dataset para identificar patrones, tendencias y relaciones entre las variables, mediante el uso de visualizaciones y consultas SQL mediante DuckDB. que permitan comprender el comportamiento de las ventas y la rentabilidad del negocio.

## Fuente 

El dataset fue descargado desde Kaggle.   
Link: https://www.kaggle.com/datasets/vivek468/superstore-dataset-final?resource=download

## Etapas

Durante el desarrollo del proyecto se realizaron las siguientes actividades:

- **Carga de datos:** Importación del archivo CSV y revisión de su estructura.
- **Análisis Exploratorio de Datos (EDA):** Identificación de tipos de datos, revisión de valores nulos, estadísticas descriptivas y análisis de las principales variables.
- **Visualizaciones:** Elaboración de gráficos para analizar ventas, ganancias, categorías de productos, regiones y otras variables relevantes.
- **Consultas SQL con DuckDB:** Integración de DuckDB para ejecutar consultas SQL directamente sobre el DataFrame, obteniendo información como ventas por categoría, ganancias por región, productos más vendidos y otros indicadores de interés para el análisis.

## Tecnologías utilizadas

- Python
- Google Colab
- Pandas
- NumPy
- Plotly

## Instrucciones para ejecutar el notebook

1. Descargar este repositorio.
2. Abrir el archivo del notebook (`notebook_analisis_sql_python.ipynb`) en Google Colab.
3. Verificar que el archivo dataset **Sample - Superstore.csv** se encuentre en la misma ubicación del notebook o cargarlo cuando el programa lo solicite.

# Análisis de Transacciones Financieras con Riesgo de Lavado de Dinero

Este proyecto analiza un conjunto de datos de transacciones financieras que presentan riesgos asociados al lavado de dinero. Se busca identificar patrones y relaciones entre las variables que pueden indicar potenciales casos de lavado de dinero.

## Contenido

- [Descripción del Dataset](#descripción-del-dataset)
- [Objetivos del Proyecto](#objetivos-del-proyecto)
- [Análisis Exploratorio de Datos (EDA)](#análisis-exploratorio-de-datos-eda)
- [Resultados](#resultados)
- [Conclusiones](#conclusiones)
- [Cómo Ejecutar el Proyecto](#cómo-ejecutar-el-proyecto)

## Descripción del Dataset

El dataset utilizado en este proyecto se encuentra en el siguiente enlace: [Big_Black_Money_Dataset.csv](https://github.com/FrancoSposetti/pre-entrega1-sposetti/blob/main/Big_Black_Money_Dataset.csv). Este archivo contiene información sobre transacciones financieras, incluyendo variables como:

- ID de Transacción
- País
- Monto (en USD)
- Tipo de Transacción
- Fecha de la Transacción
- Riesgo de Lavado
- Fuente del Dinero
- Otros detalles relevantes

## Objetivos del Proyecto

1. Realizar una limpieza y preprocesamiento de los datos.
2. Realizar un análisis exploratorio de datos (EDA) para identificar patrones y tendencias.
3. Visualizar los resultados utilizando gráficos.
4. Determinar la relación entre el monto de las transacciones y el riesgo de lavado de dinero.

## Análisis Exploratorio de Datos (EDA)

En esta sección, se presentan los pasos llevados a cabo durante el análisis exploratorio de datos:

- Carga del dataset y visualización de las primeras filas.
- Limpieza y transformación de los datos (cambio de nombres de columnas, manejo de valores nulos, conversión de tipos de datos).
- Análisis estadístico descriptivo de las variables numéricas.
- Agrupación de datos para calcular montos por país, tipo de transacción, industria, etc.
- Visualización de datos a través de histogramas, boxplots, scatter plots, y heatmaps.

## Resultados

- Se identificaron patrones en las transacciones según el monto y el riesgo de lavado de dinero.
- Se observaron distribuciones de riesgo de lavado según diferentes variables categóricas, como el tipo de transacción y la fuente del dinero.

## Conclusiones

El análisis sugiere que el monto de las transacciones no está directamente relacionado con el riesgo de lavado de dinero. El puntaje de riesgo parece ser multicausal, dependiendo de una combinación de varias variables, incluyendo el tipo de transacción, la industria, y los países de origen y destino.

## Cómo Ejecutar el Proyecto

Para ejecutar este proyecto, sigue estos pasos:

1. Clona el repositorio:
   ```bash
   git clone https://github.com/FrancoSposetti/pre-entrega1-sposetti.git

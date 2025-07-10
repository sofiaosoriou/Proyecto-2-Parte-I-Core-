# Análisis Inicial y Selección de Problema

## Descripción
Este proyecto tiene como objetivo explorar varios conjuntos de datos utilizando técnicas de análisis exploratorio de datos (EDA) para comprender su estructura, calidad y potencial de aplicación. A partir de este análisis inicial, se selecciona un problema de Machine Learning, justificando la decisión. 

## Conjuntos de Datos Analizados

1. Pingüinos: Datos biométricos de pingüinos (longitud y profundidad del pico, masa corporal, longitud de aletas y especie).  
2. Iris: Datos clásicos de flores iris, con medidas de sépalos y pétalos y su especie.  
3. Titanic: Información de pasajeros del Titanic para predecir supervivencia.  
4. Vinos: Datos fisicoquímicos de vinos para clasificar su calidad.

## Resumen del EDA Inicial

- Se exploraron valores faltantes, distribuciones, outliers y correlaciones entre variables.
- Se identificaron variables numéricas y categóricas para cada conjunto.
- Se detectaron patrones claros de separación de clases en algunos casos.

## Problema Seleccionado

Se seleccionó el conjunto de datos Pingüinos para abordar un problema de clasificación multiclase, cuyo objetivo es predecir la especie del pingüino (Adelie, Chinstrap, Gentoo) en base a características fisiológicas.

### Justificación:
- La variable objetivo es claramente categórica.
- Permite aplicar técnicas de clasificación supervisada y validación cruzada con modelos interpretables.

### Objetivo Específico:
Desarrollar, optimizar y evaluar un clasificador supervisado (Árbol de Decisión) para predecir la especie de pingüinos con la mayor precisión posible.


## Instrucciones para Ejecutar

1. Clonar este repositorio:
   git clone https://github.com/sofiaosoriou/Proyecto-2-Parte-I-Core-.git
   cd Proyecto-2-Parte-I-Core-

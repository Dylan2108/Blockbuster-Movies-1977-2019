# Análisis Estadístico de Películas Blockbuster (1977-2019)
**Proyecto de Estadística Aplicada**

## Descripción
Este proyecto realiza un análisis estadístico integral de las películas blockbuster más exitosas de los últimos 40 años. Combinando técnicas de regresión, clustering y análisis de varianza, el proyecto explora los patrones de éxito comercial, agrupa películas por características similares e identifica tendencias temporales en la industria cinematográfica.

## Objetivo
Analizar los factores que influyen en el éxito comercial de las películas blockbuster, respondiendo preguntas clave sobre presupuesto, recaudación, calificación, géneros y tendencias temporales.

## Preguntas de investigación

1- ¿Qué factores influyen en la recaudación mundial de una película?

2- ¿Podemos identificar clusters o grupos naturales de películas blockbuster según características de género, presupuesto y rating?

3- ¿Ha cambiado la recaudación promedio de los top-10 blockbusters a lo largo del tiempo?

## Estructura del proyecto

```
Blockbuster-Movies-1977-2019/
├── Analisis_Blockbusters_Main.ipynb          # Notebook principal con análisis general
├── Pregunta1_Regresion.ipynb                 # Análisis de regresión lineal múltiple
├── Pregunta2_Clustering_Peliculas.ipynb      # Análisis de clustering (K-Means)
├── Pregunta2_Clustering_Peliculas_Integrado.ipynb  # Versión integrada del clustering
├── Pregunta3_ANOVA_Tendencias_Temporales.ipynb     # Análisis ANOVA de tendencias
├── README.md                                 # Este archivo
├── data/
│   ├── Blockbusters_2019-1977.csv           # Dataset original
│   └── Blockbusters_Limpio.csv              # Dataset procesado y limpio
├── graphics/                                 # Visualizaciones generadas
│   ├── eda/                                 # Análisis exploratorio
│   ├── pregunta1/                           # Gráficos de regresión
│   ├── pregunta2/                           # Gráficos de clustering
│   └── pregunta3/                           # Gráficos de ANOVA
└── results/                                  # Resultados y conclusiones
```

## Fuente de datos
Dataset propio de las 10 películas más taquilleras de cada año (1977-2019).
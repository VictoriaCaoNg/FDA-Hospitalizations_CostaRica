# Análisis de datos funcionales del impacto de factores climáticos y de contaminación sobre las hospitalizaciones respiratorias
Este repositorio contiene el código, datos y reportes del proyecto de investigación enfocado en analizar las hospitalizaciones por enfermedades respiratorias mediante el Análisis de Datos funcionales.

## Información General
Las enfermedades respiratorias representan una importante carga económica para los sistemas de salud a nivel mundial. Su incidencia se ve fuertemente afectada por las variaciones climáticas estacionales, los factores socioeconómicos y la contaminación atmosférica. En este estudio, se propone utilizar el análisis de datos funcionales (FDA) para investigar las egresos hospitalarios semanales por enfermedades respiratorias en Costa Rica, utilizando factores climáticos como la temperatura, la precipitación, la humedad relativa y la profundidad óptica de los aerosoles como indicador de contaminación. Se ajustaron modelos lineales funcionales generalizados con diferentes distribuciones de respuesta (normal, de Poisson y binomial negativa) para evaluar la relación entre estas variables climáticas y las hospitalizaciones por enfermedades respiratorias. El modelo binomial negativo ofrece el mejor ajuste, considerando la sobredispersión de los datos. La interpretación del modelo ofrece una perspectiva informativa y novedosa desde el marco del FDA.
Si bien el análisis funcional de datos no se utiliza comúnmente en aplicaciones de salud pública, nuestros hallazgos demuestran que, cuando se aplica adecuadamente, puede proporcionar información valiosa para respaldar la toma de decisiones sanitarias basada en la evidencia.

## Estructura del repositorio
```
├── data/                       # Datos utilizados en el análisis
├── analisis_exploratorio.qmd   # Análisis exploratorio inicial
├── analisis_exploratorio.html  # Versión renderizada en HTML
├── fPCA.qmd                    # Análisis de Componentes Principales Funcionales
├── fPCA.html                   # Versión renderizada en HTML
├── regresion.qmd               # Modelo de regresión funcional
├── regresion.html              # Versión renderizada en HTML
├── analisis_exploratorio_files/  # Carpeta generada automáticamente por Quarto
├── fPCA_files/                   # Carpeta generada automáticamente por Quarto
├── regresion_files/              # Carpeta generada automáticamente por Quarto
└── README.md                   # Este archivo
```

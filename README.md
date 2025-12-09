# Functional Data Analysis of Climate and Pollution Impacts on Respiratory Hospitalizations in Costa Rica

This repository contains the code, data, and reports of the research project focused on analyzing hospitalizations for respiratory diseases through Functional Data Analysis.

## General information

Respiratory diseases pose a major economic burden on healthcare systems globally. Their incidence is strongly affected by seasonal climatic variations, socioeconomic factors, and air pollution. In this study, we propose using functional data analysis (FDA) to investigate weekly hospital discharges due to respiratory diseases in Costa Rica, using climatic factors such as temperature, precipitation, relative humidity, and aerosol optical depth as an indicator of pollution. Generalized functional linear models with different response distributions (Normal, Poisson, and Negative Binomial) are fitted to assess the relationship between these climatic variables and respiratory hospitalizations. The Negative Binomial model provides the best fit, accounting for overdispersion in the data. The interpretation of the model offers an informative and novel perspective from the FDA framework. Although functional data analysis is not commonly used in public health applications, our findings demonstrate that, when appropriately applied, it can provide valuable insights to support evidence-based healthcare decision-making.

## Repository structure
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

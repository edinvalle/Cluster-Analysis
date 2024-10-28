# Customer Clustering Analysis

Este proyecto utiliza técnicas de clustering (K-means) para segmentar clientes de un supermercado en base a tres variables: *edad, **ingresos* y *tamaño de la ciudad. El análisis incluye la exploración descriptiva de los datos, cálculos de correlación, y evaluación de la calidad del clustering mediante el **método del codo* y el *coeficiente de silueta*, permitiendo optimizar estrategias comerciales y campañas de marketing.

## Archivos del Proyecto

1. *Customer_Clustering_Analysis_Report.pdf*  
   Informe detallado del análisis, incluyendo la metodología, visualizaciones, resultados, y conclusiones obtenidas del clustering. [PDF](https://github.com/edinvalle/ClientClusterAnalysis/blob/main/Customer_Clustering_Analysis_Report.pdf  )

2. *Customer_Clustering_Analysis.html*  
   Versión interactiva del análisis en formato HTML para su visualización en navegadores web. [HTML](https://github.com/edinvalle/ClientClusterAnalysis/blob/main/Customer_Clustering_Analysis.html  )

3. *Customer_Data.xlsx*  
   Dataset utilizado para el análisis, que contiene las variables relevantes: edad, ingresos y tamaño de la ciudad. [Excel]( https://github.com/edinvalle/ClientClusterAnalysis/blob/main/Customer_Data.xlsx)

## Requisitos 
- *Lenguaje:* R
```r
# Instalar paquetes
install.packages(c("readxl", "dplyr", "ggplot2", "cluster", "factoextra", "gridExtra", "knitr"))

# Cargar paquetes
library(readxl)
library(dplyr)
library(ggplot2)
library(cluster)
library(factoextra)
library(gridExtra)
library(knitr)
```

## Cómo Ejecutar  
1. Descargar los archivos del repositorio.  
2. Abrir y explorar el informe en PDF o HTML.  
3. Utilizar el dataset Customer_Data.xlsx para replicar o ampliar el análisis en R.

# Customer Clustering Analysis

Este proyecto utiliza técnicas de clustering (K-means) para segmentar clientes de un supermercado en base a tres variables: *edad, **ingresos* y *tamaño de la ciudad. El análisis incluye la exploración descriptiva de los datos, cálculos de correlación, y evaluación de la calidad del clustering mediante el **método del codo* y el *coeficiente de silueta*, permitiendo optimizar estrategias comerciales y campañas de marketing.

## Archivos del Proyecto

1. *Customer_Clustering_Analysis_Report.pdf*  
   Informe detallado del análisis, incluyendo la metodología, visualizaciones, resultados, y conclusiones obtenidas del clustering. [PDF](https://github.com/edinvalle/ClientClusterAnalysis1/blob/main/Customer_Clustering_Analysis.pdf)

2. *Customer_Clustering_Analysis.Rmd*  
   Versión interactiva del análisis desde la aplicación de RStudio para su visualización en formato. [RMarkdown](https://github.com/edinvalle/ClientClusterAnalysis1/blob/main/Customer_Clustering_Analysis.Rmd)

3. *Customer_Data.xlsx*  
   Dataset utilizado para el análisis, que contiene las variables relevantes: edad, ingresos y tamaño de la ciudad. [Excel](https://github.com/edinvalle/ClientClusterAnalysis1/blob/main/Customer_Data.xlsx)

4. *Plantilla.tex*
   La plantilla LaTeX se utiliza para personalizar la apariencia del documento PDF generado a partir del análisis. Esta plantilla incluye configuraciones específicas como el formato de títulos, encabezados y pies de página, y otros estilos personalizados que aseguran una presentación profesional y uniforme del reporte. [Plantilla.tex](https://github.com/edinvalle/ClientClusterAnalysis1/blob/main/Plantilla.tex)

6. Integración de Imágenes
En este proyecto, se ha incluido el logo de RStudio en los documentos para asegurar una presentación profesional y coherente. [Logo de RStudio](https://github.com/edinvalle/ClientClusterAnalysis1/blob/main/images.png)
  
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


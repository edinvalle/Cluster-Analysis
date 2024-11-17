# Customer Clustering Analysis

Este proyecto utiliza técnicas de clustering (K-means) para segmentar clientes de un supermercado en base a tres variables: edad, ingresos y tamaño de la ciudad. El análisis incluye la exploración descriptiva de los datos, cálculos de correlación, y evaluación de la calidad del clustering mediante el método del codo y el coeficiente de silueta, permitiendo optimizar estrategias comerciales y campañas de marketing.

## Objetivo 

Segmentar a los clientes del supermercado mediante técnicas de clustering basadas en características y socioeconómicas: para identificar grupos y optimizar la torna de decisiones y planificación comercial. 

## Archivos del Proyecto

Adjunto los archivos del proyecto, solo que en diferentes formatos para que puedas descargarlos según tu preferencia.

1. **ClusterAnalysis_Jupyter.ipynb** Visualización rápida sin ejecutar código. [Jupyter Notebook](https://github.com/edinvalle/Cluster-Analysis/blob/main/ClientClusterAnalysis1/ClusterAnalysis_Jupyter.ipynb)


3. **Customer_Clustering_Analysis_Report.pdf** Vista rápida en PDF sin ejecutar código. [PDF](https://github.com/edinvalle/Cluster-Analysis/blob/main/ClientClusterAnalysis1/Customer_Clustering_Analysis.pdf)

4. **Customer_Clustering_Analysis.Rmd**  Requiere ejecutar el código desde RStudio para realizar el análisis. [RMarkdown](https://github.com/edinvalle/Cluster-Analysis/blob/main/ClientClusterAnalysis1/Customer_Clustering_Analysis.Rmd)

5. **Customer_Data.xlsx** Datos principales del cliente en formato Excel y CSV [Excel](https://github.com/edinvalle/Cluster-Analysis/blob/main/ClientClusterAnalysis1/Customer_Data.xlsx) [csv](https://github.com/edinvalle/Cluster-Analysis/blob/main/ClientClusterAnalysis1/Customer_Data.csv )

6. **Plantilla.tex** Plantilla para personalizar el documento final en PDF. [Plantilla.tex](https://github.com/edinvalle/Cluster-Analysis/blob/main/ClientClusterAnalysis1/Plantilla.tex)

7. **Integración de Imágenes** Imagen para la portada del documento PDF. [Logo de RStudio](https://github.com/edinvalle/Cluster-Analysis/blob/main/ClientClusterAnalysis1/images.png )

  
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



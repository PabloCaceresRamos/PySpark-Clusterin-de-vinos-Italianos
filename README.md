# Clusterin-de-vinos-Italianos
Se ha utilizado un Dataset con los resultados de un análisis químico de vinos procedente de cultivos diferentes en Italia. Utilizaremos el K-MEANS queremos agrupar las diferentes clases de vinos que tenemos. 

## Desarrollo

Para la realización del clasificador se ha utilizado el lenguaje de programación **Python** junto **PySpark** y a las librerias **Pandas**, **Seaborn** y **Matplotlib**

El entorno de desarrollo utilizado ha sido **Google Colab**.

Dataset: https://www.kaggle.com/datasets/harrywang/wine-dataset-for-clustering

## Método de clustering utilizado

**K-MEANS||**


## Metodología utilizada

El primer paso realizado ha sido el análisis de los datos proporcionados. Se ha analizado los valores vacíos, el tipo de dato de cada columna, la distribucción de cada caracteristica y la correlación, usando un mapa de calor. Los datos fueron normalizados antes de ser pasados al K-MEANS.

Una vez analizado todos los datos, se ha estudiado con el método del codo, cual era el número optimo de agrupaciones que teniamos.

Se ha creado la tubería con el clasificador, y se ha ejecutado.

Finalmente se ha analizado mediante Histogramas y gráficas de puntos la agrupación del método de cluster, pudiendo observar como la clasificación entre las 2 agrupaciones se podría hacer simplemente con dos características.

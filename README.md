# Laboratorio 4 - Inteligencia Artificial

## Segmentación de Clientes de Banco

Este proyecto implementa modelos de segmentación de clientes utilizando aprendizaje no supervisado. Se desarrollaron e implementaron los algoritmos **K-Means** y **Gaussian Mixture Models (GMM)**, tanto manualmente como con librerías, para analizar la segmentación de clientes basada en datos bancarios.

## Estructura del Proyecto

| Sección | Descripción |
|---------|------------|
| **Exploración de Datos** | Se realiza preprocesamiento, limpieza y selección de variables relevantes. |
| **K-Means desde Cero** | Implementación de K-Means sin librerías externas. Se selecciona el número óptimo de clusters usando el método del codo y la métrica de Silhouette. |
| **K-Means con Scikit-Learn** | Se utiliza Scikit-Learn para comparar resultados con la implementación manual. |
| **Gaussian Mixture Model (GMM) desde Cero** | Implementación manual de GMM con el algoritmo de Expectation-Maximization (EM). Se visualizan clusters con elipses de covarianza. |
| **GMM con Scikit-Learn** | Se compara la implementación manual con la de Scikit-Learn. |
| **Comparación y Conclusión** | Se analizan los resultados obtenidos y se justifica la elección del mejor método. |

## Métricas de Evaluación

- **Método del Codo**: Para determinar el número óptimo de clusters en K-Means.
- **Silhouette Score**: Para evaluar la calidad de la segmentación en ambos modelos.
- **Bayesian Information Criterion (BIC)**: Para seleccionar el número óptimo de componentes en GMM.

## Tecnologías Utilizadas
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn)
- **Jupyter Notebook**

## Visualización de Resultados
Se generaron gráficos para analizar la distribución de los clusters en función de las características seleccionadas y PCA:
- Distribución de datos en PCA
- Segmentación con K-Means
- Segmentación con GMM
- Elipses de covarianza para visualizar la incertidumbre en GMM

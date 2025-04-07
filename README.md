# Actividad-1 - Bootcamp ML Inteligencia Artifical

# Proyecto utilizando "Amazon Sales Dataset"

Este proyecto tuvo como objetivo realizar una limpieza, una transformación de los dato y un análisis exploratorio de datos (EDA) sobre un conjunto de datos de productos de Amazon. El conjunto de datos contiene información sobre precios, descuentos, calificaciones, entre otras cosas. A través de este análisis, se busca obtener información útil para comprender las relaciones entre las variables y hacer recomendaciones sobre estrategias de precios y descuentos.

## Descripción

El análisis se realiza utilizando Python y varias librerías para la manipulación, limpieza, visualización y análisis de datos. El flujo de trabajo incluye la carga y limpieza del conjunto de datos, la conversión de las columnas a formatos adecuados, y la visualización de los resultados para explorar las relaciones entre las variables.

## Tecnologías Utilizadas

- **Python**: Lenguaje de programación principal para el análisis de datos.
- **Pandas**: Para la manipulación de datos.
- **Numpy**: Para operaciones matemáticas y estadísticas.
- **Matplotlib** y **Seaborn**: Para la visualización de datos.
- **YData Profiling**: Para la generación automática de reportes EDA.

## Uso

1. **Carga de Datos**: El conjunto de datos de Amazon se carga desde un archivo CSV llamado `amazon.csv`. El archivo debe estar ubicado en el directorio adecuado para que el código funcione correctamente.

2. **Limpieza y Transformación de Datos**: 
   - Se eliminan valores nulos en las columnas `rating` y `rating_count`.
   - Se realiza la conversión de las columnas `discounted_price` y `actual_price` de Rupias (INR) a Dólares (USD), `rating`, `rating_count`, entre otras.
   - Se eliminan caracteres no numéricos como el símbolo de la Rupia (₹) y las comas.

3. **Análisis Exploratorio de Datos (EDA)**: Se utiliza la librería **YData Profiling** para generar un reporte EDA automático que proporciona estadísticas descriptivas, distribuciones de variables, correlaciones, gráficos y más, todo en un solo reporte para explorar las relaciones entre las variables del conjunto de datos.

## Hallazgos y Observaciones Clave

Durante el análisis, se encontraron las siguientes observaciones clave:
- **Impacto de los descuentos**: Los productos con descuentos moderados (40%-50%) tienden a generar más calificaciones, mientras que los productos con descuentos muy altos (>80%) tienden a tener calificaciones más bajas.
- **Correlación entre el número de calificaciones y la calificación promedio**: Los productos con más calificaciones tienen calificaciones promedio más estables, mientras que los productos con menos calificaciones son más susceptibles a valores extremos, entre otros que se mencionan en Notebook adjunto.


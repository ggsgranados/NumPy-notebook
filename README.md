# Numpy: Análisis numérico eficiente con Python

Este proyecto es una introducción práctica al uso de la biblioteca **NumPy** para análisis numérico y procesamiento de datos en Python, enfocándose en el manejo de arrays, visualización y análisis de series temporales de precios de manzanas en diferentes ciudades de Rusia.

## Descripción

NumPy es una biblioteca fundamental para la computación científica en Python. Proporciona:

- Objetos de matriz multidimensional (*arrays*).
- Rutinas para operaciones rápidas y eficientes sobre arrays.
- Funciones matemáticas, estadísticas y de manipulación de datos.
- Soporte esencial para áreas como análisis de datos, procesamiento de señales y aprendizaje automático.

Puedes consultar la documentación oficial en [https://numpy.org/devdocs/index.html](https://numpy.org/devdocs/index.html).

## Contenido del Proyecto

El proyecto abarca los siguientes temas:

- **Carga y manipulación de datos numéricos** desde archivos CSV remotos usando NumPy.
- **Exploración de la estructura de los arrays:** dimensiones, forma, transposición.
- **Selección y visualización de datos** con Matplotlib.
- **Comparación y análisis de series temporales**.
- **Tratamiento de valores NaN** y cálculo de estadísticas básicas.

## Estructura de los datos

El dataset contiene precios mensuales de manzanas en cinco ciudades rusas, organizado como un array de 87 filas (meses) y 5 columnas (ciudades). Los datos se cargan directamente desde un archivo CSV alojado en línea.

## Funcionalidades destacadas

- **Extracción y visualización de series temporales** por ciudad.
- **Comparación de diferentes periodos** usando slicing de arrays.
- **Comparación de arrays** con `np.array_equal` y `np.allclose`.
- **Cálculo de promedios** y manejo de valores faltantes (`NaN`).

## Requisitos

- Python 3.x
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)

## Ejecución

1. Descarga o clona este repositorio.
2. Abre el archivo `Numpy.ipynb` con Jupyter Notebook o Google Colab.
3. Ejecuta las celdas para reproducir el análisis y las visualizaciones.

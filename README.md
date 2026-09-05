# Trabajo-Fin-de-Grado-Clara
Código completo y datos utilizados para la realización del Trabajo Fin de Grado de Clara González Rosauro.

El repositorio contiene dos carpetas con los archivos de datos en formato CSV y el cuaderno Jupyter (.ipynb) con el código del análisis.

## Instalación y ejecución

Para ejecutar el código es necesario disponer de Python 3.11 y Jupyter Notebook. Las principales librerías utilizadas y sus versiones son las siguientes:
- pandas: 2.3.3
- numpy: 2.4.2
- scikit-learn: 1.8.0
- matplotlib: 3.10.8
- ipykernel: 7.2.0
- notebook: 7.5.4
- fastf1: 3.8.3

Se pueden instalar mediante: pip install pandas numpy scikit-learn matplotlib fasF1 ipykernel notebook

Una vez instaladas, se debe descargar o clonar el repositorio, mantener la estructura de las carpetas Data y LapData en el mismo directorio que el cuaderno Jupyter, abrir el archivo Trabajo_fin_de_grado_Clara.ipynb mediante Jupyter Notebook y ejecutar las celdas en orden desde el inicio. Durante la ejecución, FastF1 crea automáticamente la carpeta fastf1_cache, que no se incluye en el repositorio debido a que se trata de archivos temporales de caché. Es necesaria conexión a Internet para la obtención mediante FastF1 de los datos de los grandes premios de Las Vegas, Catar y Abu Dabi.

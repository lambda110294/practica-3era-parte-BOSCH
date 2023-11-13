Autor: Luis Guillermo Rodríguez López.

El archivo [PTfinal](PTfinal_.ipynb) muestra la creación de un modelo de inteligencia artificial utilizado para predecir alguna CLASIFICACION (según el Cátalogo CLASIFICACION_FINAL de datos de COVID). El dataset, así cpomo el diccionario de datos los puede encontrar aquí: https://datos.gob.mx/busca/dataset/informacion-referente-a-casos-covid-19-en-mexico .

En este archivo viene el preprocesamiento de los datos, así como el uso de la librería CUML (la cual es óptima para utilizar varios algortimos conocidos aprovechando una GPU). Se utilizó selección de características así como la eliminación de algunas de menos peso para el modelo. Cabe señalar que se redujo la dimesnionalidad utilizando PCA(18) para mejorar los algoritmos utilizados, sin embargo y a pesar de que se notó mejora en algunos de estos, el mejor resultado se obtuvo con el RandomForestCalssifier utilizando todas las características seleccionadas.

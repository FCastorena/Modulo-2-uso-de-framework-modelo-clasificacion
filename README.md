# Modulo-2-uso-de-framework-modelo-clasificacion
### Este repositorio muestra el trabajo hecho por para el entregable llamado "Momento de Retroalimentación: Módulo 2 Uso de framework o biblioteca de aprendizaje máquina para la implementación de una solución. (Portafolio Implementación)" para la clase Inteligencia artificial avanzada para la ciencia de datos I (Gpo 101).
### La solución a este entregable se encuentra en el jupyter notebook del repositorio "Ses06_Framework_Template.ipynb"

El propósito de este entregable es implementar un modelo de clasificación con alguno de los algoritmos de ML vistos en clase por medio de un framework, en este caso scikit-learn, el modelo de clasificación 
implementado en este caso fue un Arbol de Decisión para clasificación, el dataset utilizado para entrenar el modelo y hacer predicciones fue el breast cancer wisconsin dataset el cual es un dataset
muy utilizado para análisis de modelos de clasificación binaria, el dataset se puede cargar desde nuestro jupyter notebook con scikit-learn, detalles acerca del dataset pueden ser consultados
en el siguiente link: https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html 
El dataset puede ser descargado desde el siguiente link: https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic

El dataset tiene un total de 569 instancias y 30 variables, donde la variable a predecir es la variable 'target' que es de clase binaria, los 1 representan aquellos pacientes con tumores malignos y los 0 
tumores benignos, a continuación se muestra una breve descripción de cada una de las variables del dataset:

Información de atributos:
1. ID number
2. Diagnosis (M = malignant, B = benign)
3–32
Ten real-valued features are computed for each cell nucleus:
a. radius (mean of distances from center to points on the perimeter)
b. texture (standard deviation of gray-scale values)
c. perimeter
d) area
e) smoothness (local variation in radius lengths)
f. compactness (perimeter² / area — 1.0)
g. concavity (severity of concave portions of the contour)
h. concave points (number of concave portions of the contour)
i. symmetry
j) fractal dimension (“coastline approximation” — 1)

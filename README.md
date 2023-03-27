# Deep-Learning-CNN-Image-Classifier

🔍# Investigación #: Se realizó una investigación previa para entender el problema y las herramientas necesarias para resolverlo. En este caso, se investigó sobre el aprendizaje automático, la visión por computadora y las librerías de Python necesarias para crear el modelo.

📂 Manejo de datos: Se utilizó la librería de Python "Pillow" para cargar y procesar las imágenes de entrada, y se convirtieron en matrices numéricas de NumPy para poder ser utilizadas en el modelo.

🔢 Aprendizaje automático: Se utilizó el algoritmo "Convolutional Neural Network" (CNN) para entrenar un modelo capaz de clasificar las imágenes en dos categorías: perros y gatos. Se utilizaron 3 capas de convolución y 2 capas totalmente conectadas, con la función de activación "ReLU". La función de pérdida utilizada fue "Binary Crossentropy" y el optimizador fue "Adam".

🤖 Programación: Se utilizó el lenguaje de programación Python y se utilizaron varias librerías como TensorFlow, Keras y NumPy para implementar el modelo y entrenarlo con las imágenes de entrada.

🔎 Evaluación del modelo: Se evaluó el modelo utilizando un conjunto de datos de prueba, midiendo la precisión de la clasificación y la pérdida. Se logró una precisión del 93% en la clasificación de las imágenes.

🔧 Optimización del modelo: Se realizó un proceso de ajuste de los parámetros del modelo para lograr una mayor precisión en la clasificación de las imágenes. Se probaron diferentes valores para el número de capas, el tamaño de los filtros, la tasa de aprendizaje y otros parámetros, y se eligieron los valores que proporcionaron el mejor rendimiento.

🚀 Implementación: Finalmente, se implementó el modelo en una aplicación web utilizando la librería Flask de Python. La aplicación permite al usuario subir una imagen de un perro o un gato y devuelve una predicción de la categoría a la que pertenece la imagen.

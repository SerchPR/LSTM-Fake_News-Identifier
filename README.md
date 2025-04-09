# LSTM-Fake_News-Identifier
Red neuronal recurrente LSTM para discriminar noticias falsa a partir de la composición y estructura de su texto.

## Fake-News-dataset 
https://www.kaggle.com/datasets/abaghyangor/fake-news-dataset
*Licenced by MIT*

## Resumen del proyecto
El objetivo de este proyecto es determinar si se puede discriminar si una noticia es verdadera o falsa solamente a partir de la sintaxis y estructura utilizada, 
además de desarrollar y entrenar un modelo de red neuronal recurrente tipo LSTM.

La base de datos descargada de Kaggle cuenta con 2 archivos separados tipo .csv: "Fake.csv" y "True.csv"
En el archivo "TEXTO.ipynb" se desarrolla en python:
- Tratamiento previo de los datos.
- Creación del modelo utilizando Tensorflow.
- Entrenamiento del modelo.
- Métricas de evaluación.
- Matríz de confusión para datos de prueba.

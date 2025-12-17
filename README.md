# G-PIXEL

Este repositorio contiene los archivos utilizados en la implementación y evaluación del enfoque **G-PIXEL**, que transforma grafos en imágenes a partir de sus matrices de adyacencia para aplicar modelos de Machine Learning y Deep Learning.

## Descripción de archivos

- **cnn_GPIXEL.ipynb**  
  Notebook que define y entrena la red neuronal convolucional (CNN) sobre las imágenes de grafos, incluyendo la arquitectura, el entrenamiento y la generación de métricas por época.

  - **metricas_cnn.xlsx**  
  Archivo que almacena las métricas de desempeño de la CNN (accuracy, precision, recall y F1-score) exportadas desde `cnn_GPIXEL.ipynb`.

- **graphs_images_flat_16.csv**  
  Archivo CSV que contiene las imágenes de los grafos obtenidas desde matrices de adyacencia, redimensionadas a 16×16 y aplanadas en vectores de 256 características.

- **modelling_GPIXEL.ipynb**  
  Notebook que implementa los modelos clásicos de Machine Learning (Logistic Regression, SVC, Random Forest) y un MLP, utilizando las imágenes de grafos aplanadas como vectores de características.





# Redes neuronales convolucionales con Python y Keras

Este repositorio contiene los notebooks de seguimiento del curso de redes neuronales convolucionales con Python y Keras.

## Requisitos
- Python 3.9
- [set de imágenes](https://www.kaggle.com/datasets/alarcon7a/cnn-data-sources)
- instalación de [tensorflow](https://www.tensorflow.org/install)
- Configuración de tensorflow para [GPU](https://www.tensorflow.org/install/gpu) (opcional)
- Visual Studio Code (de preferencia)

## Instalación
1. Clonar el repositorio
2. Crear un entorno virtual con Python 3.9 de preferencia utilizando conda(si se utilizará GPU)
3. Instalar las dependencias con `pip install -r requirements.txt`
4. Ejecutar los notebooks desde Visual Studio Code o desde la terminal con `jupyter notebook`

## Contenido
- [Mi primera red](/notebooks/Mi%20primera%20red.ipynb) Contiene una red neuronal convolucional básica utilizando el dataset fashion_mnist de keras.
- [Manejo de images](/notebooks/Manejo%20de%20images.ipynb) Contiene algunas funciones para el manejo de imágenes con python.
- [Aplicación de Kernel](/notebooks/Aplicación%20de%20Kernel.ipynb) Contiene una aplicación de un kernel a una imagen.
- [Data augmentation con Keras](/notebooks/Data%20augmentation%20con%20Keras.ipynb) Contiene un ejemplo de data augmentation con keras.
- [Perros vs gatos](/notebooks/Perros%20vs%20gatos.ipynb) Contiene una red neuronal convolucional para clasificar imágenes de perros y gatos, propuesta por [Kaggle](https://www.kaggle.com/c/dogs-vs-cats).


## Licencia
[MIT](https://choosealicense.com/licenses/mit/)
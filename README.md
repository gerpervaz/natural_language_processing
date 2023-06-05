SPANISH:
Este es el código creado por tres alumnos (Jorge Galán, Germán Pérez, y Camila Valles) de la asignatura de "Comportamiento Humano e Interacción con la Inteligencia Artificial", asignatura introductoria a la Inteligencia Artificial, del grado de Ciencia de Datos e Inteligencia Artificial de la Universidad Alfonso X el Sabio. 
En primer lugar realizamos la carga del archivo csv descargado del repositorio de Kaggle obtenido mediante técnica de scrapping con reseñas positivas y negativas de la página web de booking sobre hoteles de todo el mundo (https://www.kaggle.com/datasets/thedevastator/30000-booking-com-reviews-for-hotels-worldwide?select=marketing_sample_for_booking_com-travel__20190501_20190630__30k_data.csv)

El código está pensado para ejecutarse paso por paso, dado que algunas celdas son opcionales o meras formas distintas de hacer lo mismo. Lea el texto contenido en el código para saber más de qué hace cada celda.

El código abarca los siguientes aspectos de la explotación de un archivo con esta tipología:
- Evaluación de la calidad de los datos, basado en parte en un Análisis Exploratorio de los Datos
- Limpieza de los datos
- Transformación de variables y creación de nuevas variables. En este apartado se encuentra el código que ejecuta un etiquetado mediante enfoque zero-shot que hace uso del modelo del lenguaje XLM-RoBERTa, basado en transformers.
- Descriptiva básica
- Visualización de los datos mediante gráfico de burbujas

REQUISITOS:
- El código ha sido testado en Google Colab, no obstante se podría utilizar en local con jupyter notebook u otra IDE, teniendo la precaución de eliminar las exclamaciones antes de los pip install. 
- Algunas partes del código necesitan de GPU.
- Se necesita un token de Hugging Face y puede requerir autorización de uso del modelo a través de su página web (https://huggingface.co/joeddav/xlm-roberta-large-xnli)
- Las librerias que se necesitarán son:
Librarias nativas en python:
os, re, shutil
Librerias externas (requieren instalación a no ser que ya vengan instaladas en Google Colab):
pandas, numpy, matplotlib, ydata-profiling[notebook]==4.1.0, langdetect, transformers, sweetviz, tensorflow, torch, google.colab, drive, sentencepiece

ENGLISH:
This is the code created by three students (Jorge Galán, Germán Pérez, and Camila Valles) from the course "Human Behavior and Interaction with Artificial Intelligence", an introductory subject to Artificial Intelligence, part of the Data Science and Artificial Intelligence degree at Alfonso X el Sabio University.
First, we load the CSV file downloaded from the Kaggle repository obtained through a scrapping technique with positive and negative reviews from the booking website about hotels worldwide (https://www.kaggle.com/datasets/thedevastator/30000-booking-com-reviews-for-hotels-worldwide?select=marketing_sample_for_booking_com-travel__20190501_20190630__30k_data.csv)

The code is designed to be executed step by step, as some cells are optional or just different ways of doing the same thing. Read the text contained in the code to learn more about what each cell does. Read the text contained in the code to know more about what each cell does.

The code covers the following aspects of handling a file of this type:
- Data quality assessment, partly based on an Exploratory Data Analysis
- Data cleaning
- Variable transformation and new variable creation. In this section, there is code that performs labeling using a zero-shot approach that makes use of the XLM-RoBERTa language model, based on transformers.
- Basic descriptive
- Data visualization using bubble charts

REQUIREMENTS
- The code has been tested in Google Colab, however, it could be used locally with Jupyter Notebook or another IDE, taking care to remove the exclamation marks before the pip installs. 
- Some parts of the code require a GPU.
- A Hugging Face token is required and it may require authorization for the use of the model through their website (https://huggingface.co/joeddav/xlm-roberta-large-xnli).
- The libraries that will be needed are:
Built-in Python Libraries:
os, re, shutil
External Libraries (require installation unless already installed on Google Colab):
pandas, numpy, matplotlib, ydata-profiling[notebook]==4.1.0, langdetect, transformers, sweetviz, tensorflow, torch, google.colab, drive, sentencepiece


# AI4ENG

Proyecto Análisis de Datos para Predicción de Patologías Asociadas a la Tiroides.

## Link a youtube para los videos de las entregas:

-01_Exploración_de_datos - https://youtu.be/comumN-V8gY

## Integrantes:

- Carlos Hernan Molina Bustos CC 1017247427 -
  **Bioingenieria**  

- Sara Camila Guarín Castillo CC 1000194378 -
  **Bioingenieria** 
  
  ## Dataset:
  
Los datos del proyecto vienen de la competición Kaggle Thyroid Disease Data (https://www.kaggle.com/datasets/emmanuelfwerr/thyroid-disease-data), y se pueden hacer disponibles ejecutando desde cualquier notebook en Colab los siguientes comandos:

from google.colab import files

files.upload() **En este paso el usuario debe subir su kaggle.json que descarga desde la página de kaggle, para este proyecto el usuario no debe subir ningún kaggle.json ya que se dejo dentro del notebook en colab como una variable*

!mkdir -p ~/.kaggle/ && mv kaggle.json ~/.kaggle/ && chmod 600 ~/.kaggle/kaggle.json

!kaggle datasets download -d emmanuelfwerr/thyroid-disease-data

!unzip thyroid-disease-data.zip

## Videos

- [Video primera entrega](https://youtu.be/comumN-V8gY)


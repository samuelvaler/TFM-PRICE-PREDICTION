# TFM - Predicción de Precios de Activos Financieros empleando Aprendizaje  Automático
Este repositorio contiene los Notebooks de código utilizados en mi Trabajo Final de Máster (TFM) titulado "Predicción de Precios de Activos empleando Machine Learning". El TFM se centra en el desarrollo de modelos de aprendizaje automático para predecir los precios de activos financieros.

## Contenido

El repositorio está organizado de la siguiente manera:

- El directorio `Predicciones_2019` contiene el notebook y los modelos en formato `.h5` entrenados usando datos desde el año 2010 hasta el año 2019. Dentro de este directorio encontraremos los siguientes elementos:
  - `TFM_2010_2019.ipynb` contiene el código correspondiente a la fase de entrenamiento de los modelos ya entrenados.
  - `modelos` contiene los modelos ya entrenados.
  - `Evaluacion_modelos.ipynb` contiene el código correspondiente a la fase de evaluación de los modelos.
- El directorio `Predicciones_2023` contiene el notebook y los modelos en formato `.h5` entrenados usando datos desde el año 2010 hasta el año 2023. Dentro de este directorio encontraremos los siguientes elementos:
  - `TFM_2010_2023.ipynb` contiene el código correspondiente a la fase de entrenamiento de los modelos ya entrenados.
  - `modelos` contiene los modelos ya entrenados.
  - `Evaluacion_modelos.ipynb` contiene el código correspondiente a la fase de evaluación de los modelos.
- El archivo `Analisis_de_datos.ipynb` contiene el código empelado para el análisis previo de los datos de train y test.
- El archivo `requirements.txt` contiene los requisitos necesarios para ejecutar los notebooks.
- El archivo `LICENSE.txt` contiene la información relativa a la licencia de uso de este código.

## Requisitos

Los siguientes requisitos deben cumplirse para ejecutar los Notebooks:

- Python 3.7 o superior
- Bibliotecas de Python: yfinance, pandas, numpy, scikit-learn, matplotlib, seaborn, y keras.

## Instrucciones de uso

1. Clona el repositorio en tu máquina local:
git clone https://github.com/samuelvaler/TFM-PRICE-PREDICTION

2. Asegúrate de tener los requisitos necesarios instalados en tu entorno de desarrollo. Las dependencias requeridas se encuentran en el archivo `requirements.txt` y se instalan con:
pip install -r requirements.txt

3. Se generará una carpeta con el nombre `TFM-PRICE-PREDICTION`. En esta carpeta estarán todos los archivos mencionados en la sección `Contenido`.

## Autor
Todo el código expuesto en este trabajo ha sido creado íntegramente por Samuel Valer Nasta.

## Contribuciones

Las contribuciones a este repositorio son bienvenidas. Si tienes alguna sugerencia, corrección o mejora, por favor crea una issue o envía una pull request.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más información.

## Contacto

¡Gracias por visitar este repositorio! Si tienes alguna pregunta o consulta relacionada con este trabajo, no dudes en contactarme por correo electrónico a samuelvalernasta@gmail.com.



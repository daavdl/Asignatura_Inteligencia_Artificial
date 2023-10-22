# Asignatura_Inteligencia_Artificial
Este repositorio contendrá todos los trabajos realizados en la asignatura Introducción a la inteligencia artificial.

Integrantes del grupo:
  Michael Stiven Zapata Giraldo - 1017172358 - Ingenieria Electrica
  Daniel Vergara de Leon - 1002388181 - Ingenieria Electrica

Enlace al dataset en kaggle:
  https://www.kaggle.com/competitions/playground-series-s3e20/data?select=train.csv

Instrucciones para obtener los datos en el colab:
  1. Abrimos el enlace anterio donde encontraremos la competencia de kaggle, nos incribimos a la competencia y aceptamos las reglas.
  2. En la pagina de kaggle nos vamos a la opcion de configuracion, aquí crearemos un token en el indice API.
  3. Al completar el paso anterior se nos descargará un archivo .json con nuestro username y una key.
  4. Ya en el colab al correr la celda que contiene:
         dataset_url = 'https://www.kaggle.com/competitions/playground-series-s3e20/data?select=train.csv'
         od.download(dataset_url)
     Se nos abrirá un espacio, primero ingresamos el username y luego la key que nos dio el archivo .json
  5. Así ya tenemos acceso al dataset en el colab. 

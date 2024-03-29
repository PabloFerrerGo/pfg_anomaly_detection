# Introducción

En este repositorio se puede encontrar el código utilizado en el trabajo de fin de grado "Detección de anomalías en imágenes, estudio del problema y aplicación de la librería Anomalib" realizado por Pablo Ferrer González. Este repositorio esta también documentado con la finalidad de facilitar el uso de la librería Anomalib a un hipotético lector que quiere comenzar a desarrollar soluciones con dicha librería.

# Instalación

En la consola de comandos Anaconda Prompt:

   ```sh
   conda create -n anomalib_env python=3.8
   conda activate anomalib_env
   pip install anomalib
   pip install keras
   pip install tensorflow
   pip install paho-mqtt
   pip install thingspeak
   ```
   
  # Sobre los archivos del repositorio
  
  - `IoT - PYNQ` y `IoT - Server` se corresponden con los notebooks que han sido necesarios para implementar el caso práctico.
  - `Model training` trata de cómo entrenar un modelo de Anomalib.
  - `Model boosting` desarrolla los procedimientos para realizar Data Augmentation, Transfer Learning e Hyperparameter Tuning
  - `datos_naranjas.zip` se corresponde con el conjunto de datos propio que se ha creado para el caso práctico y utilizado también para la obtención de resultados en el apartado de Data Augmentation
  - `anomalib/models` contiene los modelos de Anomalib que se han utilizado y sus respectivas configuraciones, las cuales podemos encontrar en los archivos .yaml
  - `results` en esta carpeta pueden encontrarse imágenes generadas por el código de la librería Anomalib, las cuales muestran los mismos resultados en las métricas que las que aparecen en `4.2.1 Data augmentation`, `4.2.3. Hyperparameter Tuning` y `5.1. Descripción del caso práctico`.

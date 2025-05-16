# ARQUITECTURAS EMPRESARIALES - PROYECTO FINAL

# Inteligencia artificial para pagos seguros.

### Introducción 

El objetivo de este proyecto es construir un modelo que pueda determinar si una transacción con tarjeta de crédito es fraudulenta. Con un enfoque de aprendizaje supervisado. Con visualizaciones para  comprender la estructura de los datos y descubrir patrones interesantes.

### Prerrequisitos


* [JupyterLab](https://jupyter.org) - Entorno de desarrollo interactivo el desarrollo de Jupyter Notebooks. 
* [Python ](https://www.python.org) - Lenguaje de alto nivel de programación interpretado.
* [Git](https://git-scm.com/) - Sistema de control de versiones


## Construido con 

* [SageMaker](https://aws.amazon.com/es/sagemaker/) - Amazon SageMaker es una plataforma de aprendizaje automático.

* [Python](https://www.python.org) - Lenguaje de alto nivel de programación interpretado.

* [pandas](https://pandas.pydata.org) - Pandas es una librería de Python especializada en el manejo y análisis de estructuras de datos.

* [Amazon S3](https://aws.amazon.com/es/s3/) - Servicio de almacenamiento de objetos que ofrece escalabilidad, disponibilidad de datos, seguridad y rendimiento.

### Desarrollo

En este proyecto, se analizaron un conjunto de datos de transacciones con tarjetas de crédito realizadas durante un período de dos días, El conjunto de datos contiene 284.807 transacciones, de las cuáles 492 fueron catalogadas fraudulentas es decir el 0,17%  de las transacciones analizadas.Cada transacción tiene 30 características, todas ellas numéricas. Las características V1 a V 28
son el resultado de una transformación PCA, para poder proteger la confidencialidad por ello la información básica sobre estas funciones no está disponible. La función Tiempo contiene el
tiempo transcurrido desde la primera transacción, y la función Monto contiene el monto de la transacción. La variable de respuesta Clase, es 1 en el caso de fraude y 0 en caso contrario.

### Vídeo funcionamiento:
https://github.com/juliandtrianar/Proyecto_AREP/blob/464deeff867937056c748776d9034a5022f0466b/prototipo.mp4

## Autor

- **Julián David Triana Roa**

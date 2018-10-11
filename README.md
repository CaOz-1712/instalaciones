# Instalación (Pasos del primer correo):

python -V

conda create -n py34 python=3.4 anaconda

conda activate py34

conda install -c anaconda git

conda install -c anaconda jupyter

conda install -c anaconda numpy

conda install -c anaconda matplotlib

conda install anaconda-client

conda install --channel https://conda.anaconda.org/menpo opencv3

conda update --all


# Verificación de instalación

Probablemente te preguntes ¿Cómo puedes comprobar que tu instalación es correcta? 


## Clonación de este repositorio

Desde tu ventana de comandos de Anaconda, ejecuta la siguiente línea:

git clone https://github.com/SandraFB/instalaciones.git

![clone](https://github.com/SandraFB/instalaciones/blob/master/imagen1.jpg)


![path](https://github.com/SandraFB/instalaciones/blob/master/imagen2.jpg)


Si te apareció el error que te hace falta "git", escribe:

conda install -c anaconda git


Anota la dirección en la que clonaste el directorio de "instalaciones" (observa que está indicado con recuadros anaranjados en la imagen anterior).

![path2](https://github.com/SandraFB/instalaciones/blob/master/imagen4.jpg)


Abre el directorio en donde clonaste el repositorio con el comando "cd", como se muestra en la siguiente imagen.


![cd](https://github.com/SandraFB/instalaciones/blob/master/imagen14.jpg)



## Puesta en práctica

1. Vamos a generar otro entorno virtual para OpenCV2 (el cual ocuparemos para la práctica de calibración durante el curso). 

Desde Anaconda, escribe las siguientes líneas de código:


conda create -n py27 python=2.7 anaconda

activate py27

conda install -c https://conda.anaconda.org/conda-forge opencv

jupyter notebook


![Jupyter](https://github.com/SandraFB/instalaciones/blob/master/imagen15.jpg)



2. Ahora, desde Jupyter Notebook, crearemos un nuevo documento:


![Nuevo](https://github.com/SandraFB/instalaciones/blob/master/imagen3.jpg)


![Nuevo Notebook](https://github.com/SandraFB/instalaciones/blob/master/imagen6.jpg)


3. Importamos librerías escribiendo el siguiente código en el Notebook creado y ejecutamos:

import numpy as np

import cv2

import glob

import matplotlib.pyplot as plt

import pickle

%matplotlib inline

%matplotlib qt

Nota: Estas líneas de código importan las librerías mencionadas. Si no te marca error, has instalado correctamente las librerías.

cv2.__version__ 

Nota: Esta línea de código imprime la versión de OpenCV instalada. Si no te marca error, has instalado correctamente OpenCV.


![Notebook](https://github.com/SandraFB/instalaciones/blob/master/imagen7.jpg)


![Código](https://github.com/SandraFB/instalaciones/blob/master/imagen8.jpg)


4. Prácticas en Python

A forma de taller introductorio para Python, puedes ejecutar las prácticas 1, 2 y 3 en Jupyter Notebook.

Primero selecciona la práctica a realizar y abre el enlace.


![Selección](https://github.com/SandraFB/instalaciones/blob/master/imagen9.jpg)


Después, ejecuta el código línea por línea y observa el resultado.


![Ejecución](https://github.com/SandraFB/instalaciones/blob/master/imagen10.jpg)



## Referencias

1. Python 3.6 documentation.

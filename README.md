# PygroupIA

Es una rama de pygroup de ACMUD, la cual está orientada al machinelearning.

En clases está el material que corresponde a python desde 0 a objetos, uso de librerías y ciencia de datos; y machine learning.

Para referencia mi kaggle [msjimenezc](https://www.kaggle.com/msjimenezc), subo de vez en cuando código.


Parte del código que corresponde a modelos de IA pertenece a:
* [Tensorflow image classification](https://www.tensorflow.org/tutorials/images/classification?hl=es)
* [Tensorflow text classification](https://www.tensorflow.org/tutorials/keras/text_classification?hl=es)
* [Tensorflow GANS](https://www.tensorflow.org/tutorials/generative/dcgan?hl=es)

## Ejecución
Si quieres ejecutarlo en local, requieres del módulo venv de python para hacer entornos virtuales.
### Windows
En windows venv viene con python, asi que no hay pasos adicionales, asi que se crea el venv en CMD o powershell:
```sh
py -m venv nombre-entorno
```
o
```sh
python -m venv nombre-entorno
```
Luego hay que ejecutar el entorno:
```sh
.\nombre-entorno\Scripts\activate
```
### Linux
En linux es un tanto diferente, en derivados de Arch como Manjaro ya tiene instalado venv, sin embargo derivados de Ubuntu y Debian no, y para instalarlo en dichos sistemas operativos se usa:
```sh
sudo apt install  python3-venv
```
Luego se crea el entorno virtual con:
```sh
 python3 -m venv nombre-entorno
```
Para abrirlo se usa:
```sh
source nombre-entorno/bin/activate
```
### Instalar jupyter
Si aparece el nombre del entorno entre parentesis antes de la linea en nuestro CMD está correcto.
Ahora hay que instalar jupyter notebook.
```sh
pip install jupyter
jupyter notebook
```
y para desactivar el entorno virtual
```sh
deactivate
```

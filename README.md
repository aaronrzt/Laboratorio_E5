# Laboratorio_E5

## Setup
Es requerido tener instalado las librerias Open Camera Vision (OpenCV), matplotlib y Numpy para que funcione el proyecto, en caso de no tenerlas instaladas, se requerirá ingresar en la consola los siguientes comandos:

Para instalar el módulo de Open Camera Vision (OpenCV) de python:

```
pip install opencv-python
```
Para instalar el módulo de Matplotlib de python:

```
pip install matplotlib
```
Para instalar el módulo de Numpy de python:

```
pip install numpy
```

## Funcionamiento
En su estado aactual, el programa toma la imagen *Testing.jpg* y genera su matriz a escala de grises, donde guarda esta matriz como imagen. Una vez hecho esto, se aplica una convolución usando el filtro proporcionado por el usuario al llamar la función *convolution*.

El programa nos permite ver sus dimensiones, junto con las dimensiones del filtro kernel que será aplicado, y los tamaños de las matrices usadas junto con sus modificaciones de tamaño. Para asegurarnos que el procedimiento es correcto actualmente, se mantuvo un caso de prueba; se importa la imagen mencionada anteriormente (*Testing.jpg*) y se le aplica una convolución usando un kernel en la función declarada.

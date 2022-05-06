# myeyes trainer
Notebook python para el entrenamiento de un modelo personalizado basado en el zoo de modelos de Tensorflow para el reconocimiento de objetos en TFLite

## Features
- Entrenamiento personalizado de un modelo del [Zoo de Tensorflow](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf2_detection_zoo.md)
- Conversion de modelo a TFLite

## Instalacion 
1) Instalar [Anaconda](https://www.anaconda.com/products/distribution)
2) Generar enviroment con:
- Tensorflow
- Tensorflow-GPU
```bash
conda create --name [env name] tensorflow tensorflow-gpu
```
3) Inicializar enviroment
```bash
conda activate [env name]
```
4) Instalar [Jupyter](https://anaconda.org/anaconda/jupyter)
```bash
conda install -c anaconda jupyter 
```
5) Inicia Jupyter
6) Abrir Trainer.ipynb, descomentar instaladores pip en primer recuadro e instarlos
7) Realizar ajustes necesatios

### Ajustes 
1) Una vez creada la estructura de carpetas copiar el dataset (iamgenes jpg) en la carpeta ```workspace/data/images``` y el conjunto de etiquetas xml en ```workspace/data/annotations```

## Tecnologias
El proyecto fue creado con :
* Tensorflow: 2.8.0

## Herrramientas
El proyecto utiliza las siguientes herramientas:
* [jupyter Notebooks](https://jupyter.org/)
* [labelimg](https://github.com/tzutalin/labelImg)


### Notas
- TFLite para Deteccion de objetos solo acepta modelos de la familai SSD, actualmente la aplicacion usa **SSD MobileNet v2 320x320**


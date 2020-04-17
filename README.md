# Crear Libreria En Arduino


**Palabras De colores**: Se crea un archivo con el nombre de cualquier palabra para que esa palabra en el editor de texto del arduino cambie de color como al color verde, esto es utilizado para diferenciar las palabras reservadas.

Dentro del arduino se presiona CONTROL+shifth+N para crear un archivo se crea dos archivos uno "libreria.h" y otro "libreria.cpp" la razon por la cual se crean dos archivos es que uno llama include "libreria.h" todo el codigo se ejecuta en nuestra funcion principal es decir si en esa parte hemos creado variables se crearan en nuestra seccion principal la razon por la cual se crea el otro archivo es para que solo esten reservadas las funciones y variables que queremos utilizar como funcion();   


## Sketch
```c++
#include "libreria.h"

void setup() 
{
  funcion();
}

void loop() 
{
}
```
* Invoca funciones incluidas en la libreria

## libreria.h
```c++

void funcion()
{
  Serial.begin(9600);
  Serial.println("hola mundo");
}
```
* Este archivo contiene las funciones de la libreria

# Crear una Libreria En Arduino


<p align="center">
  <img  src="https://github.com/IDiegoUlises/Arduino-Crear-Libreria/blob/master/Images/library-fondo-black.png">
</p>



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
* **Invoca una funcion de la libreria**

## libreria.h
```c++

void funcion()
{
  Serial.begin(9600);
  Serial.println("hola mundo");
}
```
* **Este archivo contiene las variables y funciones**

## Debug
<img  src="https://github.com/IDiegoUlises/Arduino-Crear-Libreria/blob/master/Images/puerto-serial.png">

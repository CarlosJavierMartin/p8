# Tarea 8 CIU

Autor: Carlos Javier Martín Perdomo

Descripción: Siguiendo las restricciones de la practica, el archivo sketch.js tiene un peso final de: ![error](https://github.com/CarlosJavierMartin/p8/blob/master/Images/image.png?raw=true). En ese archivo se puede encontrar todo el código en "formato ahorro". A continuación expondré el código de forma mas visual para que se pueda ver el mismo con claridad. A su vez ire explicando cada parte del código:

Código y decisiones adoptadas para la solución propuesta:
  - En el setup y la creación de variables inicializo el numero máximo de elipses a 2000 y creo el vector que las contendrá. Introduzco en este vector el primer elemento que sera el que se mantenga siempre en pantalla. También inicializo una variable de control "b" que indica si estoy metiendo o sacando elementos del vector. Inicializo también las variables "i" e "y" que serán usadas en los bucles
  
  ![error](https://github.com/CarlosJavierMartin/p8/blob/master/Images/setup.jpeg?raw=true)
  
  - La clase "eo" representa una elipse en movimiento. Cada elipse es creada de forma completamente aleatoria a excepción de su velocidad y dirección (variables dx y dy) que están enmarcadas dentro de un rango mas concreto. El método dis() se encarga de mostrar la elipse en la posición correspondiente con el color y la transparencia correspondientes. El método move(f) se encarga de cambiar la posición de la elipse para crear la sensación de movimiento y que esta rebote en los bordes correctamente. Por ultimo el método border() devuelve si en ese momento la elipse esta en el borde. Si se produce esta ultima acción, en el draw se creara una nueva elipse.

  ![error](https://github.com/CarlosJavierMartin/p8/blob/master/Images/draw.jpeg?raw=true)
  
  - En el draw gestiono la creación de objetos de la clase que representara las elipses. Gestiona la introducción y eliminación de estos objetos en el vector según corresponda.
  
  ![error](https://github.com/CarlosJavierMartin/p8/blob/master/Images/class.jpeg?raw=true)
  
  Ejemplo de fases de ejecución del código:
  
  ![error](https://github.com/CarlosJavierMartin/p8/blob/master/Images/fase1.jpeg?raw=true)
  
  ![error](https://github.com/CarlosJavierMartin/p8/blob/master/Images/fase2.jpeg?raw=true)
  
  ![error](https://github.com/CarlosJavierMartin/p8/blob/master/Images/fase3.jpeg?raw=true)
  
  El resultado se puede encontrar accediendo al siguiente enlace: https://editor.p5js.org/carlos.martin/present/4foJBMHys
  
  
  Referencias:
  - Recursos de programación:
    - https://p5js.org/reference/
    - Web usada para el programa: https://editor.p5js.org/

# Tarea 8 CIU

Autor: Carlos Javier Martín Perdomo

Descripcion: Siguiendo las restricciones de la practica, el archivo sketch.js tiene un peso final de: ![error](https://github.com/CarlosJavierMartin/p8/blob/master/Images/image.png?raw=true). En ese archivo se puede encontrar todo el codigo en "formato ahorro". A continuacion expondre el codigo de forma mas visual para que se pueda ver el mismo con claridad. A su vez ire explicando cada parte del codigo:

Codigo y decisiones adoptadas para lña solución propuesta:
  - En el setup y la creacion de variables inicializo el numero maximo de elipses a 2000 y creo el vector que las contendra. Introduzo en este vector el primer elemento que sera el que se mantenga siempre en pantalla. Tambien inicializo una variable de control "b" que indica si estoy metiendo o sacando elementos del vector. Inicializo tambien las variables "i" e "y" que seran usadas en los bucles
  
  ![error](https://github.com/CarlosJavierMartin/p8/blob/master/Images/setup.jpeg?raw=true)
  
  - La clase "eo" representa una elipse en movimiento. Cada elipse es creada de forma completamente aleatoria a excepcion de su velocidad y direccion (variables dx y dy) que estan enmarcadas dentro de un rango mas concreto. El metodo dis() se encarga de mostrar la elipse en la posicion correspondiente con el color y la trqansparencia correspondientes. El metodo move(f) se encarga de cambiar la posicion de la elipse para crear la sensacion de movimiento y que esta rebote en los bordes correctamente. Por ultimo el metodo border() devuelve si en ese momento la elipse esta en el borde. Si se produce esta ultima accion, en el draw se creara una nueva elipse.
  
  ![error](https://github.com/CarlosJavierMartin/p8/blob/master/Images/draw.jpeg?raw=true)
  
  - En el draw gestiono la creacion de objetos de la clase que representara las elipses. Gestiona la introduccion y eliminacion de estos objetos en el vector segun corresponda.
  
  ![error](https://github.com/CarlosJavierMartin/p8/blob/master/Images/class.jpeg?raw=true)
  
  Ejemplo de fases de ejecucion del codigo:
  
  ![error](https://github.com/CarlosJavierMartin/p8/blob/master/Images/fase1.jpeg?raw=true)
  
  ![error](https://github.com/CarlosJavierMartin/p8/blob/master/Images/fase2.jpeg?raw=true)
  
  ![error](https://github.com/CarlosJavierMartin/p8/blob/master/Images/fase3.jpeg?raw=true)
  
  El resultado se puede encontrar accediendo al siguiente enlace: https://editor.p5js.org/carlos.martin/present/4foJBMHys
  
  
  Referencias:
  - Recursos de programación:
    - https://p5js.org/reference/
    - Web usada para el programa: https://editor.p5js.org/

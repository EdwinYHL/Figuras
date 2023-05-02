***
# *Tarea de Polimorfismo*
***
*Tabla de contendo.*
1. Paradigma OO.
* Definición de Paradigma.
* Definición de Programación Orientada a Objetos.
2. UML.
* Diagrama.

---


## 1. 
Este código es una implementación del juego de Flappy Bird en JavaScript. En el juego, el jugador controla un pájaro que debe pasar a través de tuberías que se mueven hacia la izquierda en la pantalla. El objetivo del juego es obtener la mayor cantidad de puntos posible al pasar por las tuberías sin chocar contra ellas o tocar el suelo.

*Variables y constantes:
El código comienza definiendo algunas variables y constantes. GRAVITY, JUMP_HEIGHT y GROUND_HEIGHT se refieren a la gravedad, la altura del salto del pájaro y la altura del suelo, respectivamente. WIDTH y HEIGHT representan el ancho y la altura de la ventana del juego. SCROLL_SPEED es la velocidad a la que se mueven las tuberías y SCORE es el puntaje del jugador.

Funciones:
El código define dos funciones. La primera, getRndInteger(min, max), genera un número aleatorio entre min y max. La segunda, setup(), se llama una vez al comienzo del juego y crea la ventana del juego utilizando createCanvas() de p5.js.

Clases:
El código define dos clases. La primera, Bird, representa al pájaro del juego. Tiene atributos como la posición del pájaro y su velocidad vertical. También tiene métodos para dibujar el pájaro, actualizar su posición y verificar si ha chocado con una tubería. El segundo, Pipes, representa las tuberías del juego. Tiene atributos como el ancho de las tuberías y la distancia entre ellas, y métodos para dibujar las tuberías y actualizar su posición.

El constructor:
Después de definir las clases, el código crea instancias de Bird y Pipes utilizando sus constructores. El constructor de Bird toma tres argumentos: la posición inicial x y y del pájaro y el tamaño del pájaro. El constructor de Pipes toma tres argumentos: el ancho de las tuberías, la frecuencia con la que aparecen las tuberías y la distancia entre ellas.

La función draw():
La función draw() se llama repetidamente por p5.js para dibujar la ventana del juego. La función comienza dibujando el fondo y el suelo del juego. Luego dibuja y actualiza el pájaro y las tuberías. Finalmente, dibuja el puntaje del jugador.

Eventos de teclado y ratón:
El código define dos funciones, keyPressed() y mouseClicked(), que se llaman cuando el usuario presiona una tecla o hace clic en el mouse, respectivamente. Ambas funciones llaman al método flap() de Bird para hacer que el pájaro salte.

El juego consta de dos clases principales: Bird (pájaro) y Pipes (tuberías). La clase Bird se encarga de manejar el movimiento del pájaro y detectar cuando el pájaro ha chocado con una tubería o el suelo. La clase Pipes se encarga de manejar las tuberías que aparecen en la pantalla y moverlas hacia la izquierda.

La variable SCORE mantiene un registro de la puntuación del jugador. El jugador gana un punto por cada tubería que pasa con éxito.

La función setup() inicializa el juego y crea la ventana de juego usando la función createCanvas() de p5.js.

La función draw() se llama en un bucle continuo y se encarga de dibujar los objetos del juego en la pantalla, actualizar sus posiciones y detectar las interacciones entre ellos.

La función keyPressed() detecta cuando se presiona la tecla espaciadora y hace que el pájaro salte.

La función mouseClicked() hace lo mismo que keyPressed(), permitiendo que el usuario haga que el pájaro salte haciendo clic en la pantalla.

En general, este código es un buen ejemplo de cómo se puede implementar un juego simple usando JavaScript y p5.js.

***
# *UML: Diagrama de clases*
***

---
# Referencias.
[^1]: M. (2022, 14 marzo). ¿Qué son los paradigmas de programación? Profile Software Services. https://profile.es/blog/que-son-los-paradigmas-de-programacion/
[^2]: M. (2022, 14 marzo). ¿Qué son los paradigmas de programación? Profile Software Services. https://profile.es/blog/que-son-los-paradigmas-de-programacion/

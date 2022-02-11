# Juego-Phaser-Javascript-Trabajo-02

Con esta actividad pude practicar algunas bases de Javascript. 
El trabajo consistó en modificar un pequeño juego de Phaser utilizando el código fuente de un zip, proporcionado por la página web http://phaser.io/tutorials/making-your-first-phaser-3-game-spanish

El zip contenía todas las partes de un tutorial para programar este juego usando Javascript en un archivo html. 
Únicamente modifiqué el archivo "part10.html", ya que era el que contenía el código completo. 

Hice las siguientes modificaciones: 

Definí dos variables más, uno para el mensaje de fin de juego y otro para el indicador de vida, para que el juego no termine con una sola vez de chocar con una bomba.

![image](https://user-images.githubusercontent.com/97979648/153528472-3009e818-5c88-47b6-8f35-c43f8ac75828.png)

Posteriormente creé dos nuevas plataformas para que estén en la parte superior de la pantalla, además de modificar un poco la ubicación de las demás.

![image](https://user-images.githubusercontent.com/97979648/153528887-7ffe0733-5c34-4f4c-b521-9e0423331cf0.png)

Aquí defino el texto de la vida, además de modificar el color y la ubicación del indicador de puntuación. 

![image](https://user-images.githubusercontent.com/97979648/153529115-f9cf6387-7c27-43c4-9549-dadfa6a3f420.png)

Aquí modifiqué los parámetros de la velocidad del jugador al pulsar determinados botones del cursor, más que nada para que el personaje sea más rápido.

![image](https://user-images.githubusercontent.com/97979648/153529236-263a70c0-fb3c-438d-a7a9-a7006cf72a7e.png)

Finalmente, en la función hitbomb implementé una condición de fin de juego. La vida del jugador inicia con 100 y cada colisión con alguna bomba le baja 10 puntos. Cuando esa variable llegue a 0, el juego terminará y se desplegará el mensaje de fin de juego en el centro.

![image](https://user-images.githubusercontent.com/97979648/153529436-def13656-48d8-49ed-916b-03b1a92263a9.png)




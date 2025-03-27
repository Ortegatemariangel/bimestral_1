# bimestral_1

Este es un juego simple desarrollado con Python y Pygame, en el que el jugador o usuario controla un cohete que debe esquivar planetas mientras suma puntos.

## Cómo Jugar

- Para mover el cohete: Usa la flecha derecha.

- Debes evitar chocar: Si chocas con un planeta o sales de la pantalla el juego se acaba.

- Debes sumar puntos: Ganas un punto cada vez que un planeta desaparece sin chocar contigo.

- Para salir: Presiona ESC para cerrar el juego.

## Herramientas

- Importamos pygame

- Importamos random import randint

- El juego usa imágenes almacenadas en la carpeta img:

- imgCOHETE.png = Cohete del jugador.

- imgPLANETA.png = Planeta a esquivar.


## Processing

- Se configura la ventana y se cargan las imágenes.

- Se definen ls variables que son las posiciones y tamaños del cohete y los planetas.

- Se ejecuta un bucle que:

- Procesa eventos de teclado.

- Mueve los planetas y el cohete.

- Detecta choques.

- Actualiza la pantalla.

## Output 

- El juego finaliza si hay un choque o si el cohete se sale de la pantalla.

# Diseño

![Diagrama](diagrama.png "Diagrama de flujo")
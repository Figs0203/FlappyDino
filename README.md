# FlappyDino

Un juego estilo Flappy Bird desarrollado en Jack (lenguaje de programación del curso Nand2Tetris), donde controlas un pterodáctilo que debe esquivar meteoritos mientras navega entre espinas mortales.

## Descripción del Juego

FlappyDino es un juego de acción y supervivencia donde el jugador controla un pterodáctilo que vuela a través de un paisaje lleno de peligros. El objetivo es sobrevivir el mayor tiempo posible esquivando meteoritos que se mueven de derecha a izquierda, mientras evitas las espinas mortales ubicadas en la parte superior e inferior de la pantalla.

### Características

- **Meteoritos dinámicos**: 5 meteoritos independientes que se mueven continuamente de derecha a izquierda
- **Variedad visual**: Dos tipos diferentes de sprites de meteoritos que se alternan para mayor variedad
- **Espinas mortales**: Espinas en movimiento en la parte superior e inferior de la pantalla que matan al jugador al contacto
- **Sistema de puntuación**: El score aumenta cada vez que un meteorito sale completamente del mapa por el lado izquierdo

### Objetivo

Sobrevive el mayor tiempo posible esquivando meteoritos y espinas. Tu puntuación aumenta cada vez que un meteorito completa su recorrido y sale del mapa. ¡Intenta conseguir la puntuación más alta posible!

## Equipo de Desarrollo

Este juego fue desarrollado por:

- **Agustín Figueroa**
- **Sofía Gallo**
- **Sofía Vélez**

## Tecnologías

- **Lenguaje**: Jack (Nand2Tetris)
- **Plataforma**: Hack Computer / VM Emulator

## Video del proyecto
https://youtu.be/WzQTht0MdEQ

## Estructura del Proyecto

- `Game.jack`: Lógica principal del juego, manejo de estados y colisiones
- `Player.jack`: Control del pterodáctilo, física y animaciones
- `Meteorito.jack`: Lógica de los meteoritos, movimiento y detección de salida
- `Score.jack`: Sistema de puntuación
- `SpriteManager.jack`: Gestión de sprites y dibujo de elementos visuales

---

¡Disfruta jugando FlappyDino!


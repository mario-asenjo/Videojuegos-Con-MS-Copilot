# Documento de diseño del videojuego

## 1. Nombre del juego

Meteor Defender

## 2. Idea general

El jugador controla una nave espacial que debe defender la Tierra destruyendo meteoritos que caen desde la parte superior de la pantalla.

El objetivo es sobrevivir el mayor tiempo posible y conseguir la máxima puntuación.

## 3. Tipo de juego

Juego arcade 2D sencillo, inspirado en juegos clásicos de disparos espaciales.

## 4. Público objetivo

Personas de cualquier edad. El juego debe ser fácil de entender en pocos segundos.

## 5. Plataforma

Navegador web.

Debe funcionar como un único archivo `index.html`, usando HTML, CSS y JavaScript puro.

No debe usar librerías externas.

## 6. Controles

- Flecha izquierda o tecla A: mover la nave a la izquierda.
- Flecha derecha o tecla D: mover la nave a la derecha.
- Barra espaciadora: disparar.
- Enter: empezar o reiniciar la partida.

## 7. Elementos del juego

### Jugador

Una nave situada en la parte inferior de la pantalla.

La nave puede moverse horizontalmente, pero no puede salir de los límites de la pantalla.

### Enemigos u obstáculos

Meteoritos que aparecen en posiciones aleatorias en la parte superior y caen hacia abajo.

### Disparos

La nave puede disparar proyectiles hacia arriba.

Si un proyectil toca un meteorito, el meteorito desaparece y el jugador gana puntos.

## 8. Reglas

- El jugador empieza con 3 vidas.
- Cada meteorito destruido suma 10 puntos.
- Si un meteorito toca la nave, el jugador pierde 1 vida.
- Si un meteorito llega a la parte inferior de la pantalla, desaparece sin quitar vida.
- Cuando las vidas llegan a 0, la partida termina.
- La dificultad debe aumentar poco a poco con el tiempo.

## 9. Pantallas

El juego debe tener:

### Pantalla de inicio

Debe mostrar:
- Nombre del juego.
- Breve explicación.
- Controles.
- Mensaje: “Pulsa Enter para empezar”.

### Pantalla de juego

Debe mostrar:
- Nave.
- Meteoritos.
- Disparos.
- Puntuación.
- Vidas.

### Pantalla de fin

Debe mostrar:
- Mensaje “Game Over”.
- Puntuación final.
- Mensaje “Pulsa Enter para reiniciar”.

## 10. Estilo visual

- Fondo oscuro con estrellas.
- Nave de color claro o azul.
- Meteoritos de color naranja o marrón.
- Disparos luminosos.
- Texto grande y legible.
- Aspecto arcade sencillo.

## 11. Requisitos técnicos

- Todo el juego debe estar en un único archivo `index.html`.
- El archivo debe incluir HTML, CSS y JavaScript.
- No usar imágenes externas.
- No usar sonidos externos.
- No usar librerías.
- El código debe estar comentado de forma sencilla.
- Debe funcionar al abrir el archivo directamente en un navegador moderno.

## 12. Prioridades

1. Que el juego funcione.
2. Que sea fácil de entender.
3. Que se pueda jugar inmediatamente.
4. Que el código sea sencillo.
5. Que sea visualmente agradable.
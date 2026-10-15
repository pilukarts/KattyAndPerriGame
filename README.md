# Katty And Perri Game

Prototipo de mascotas virtuales en pixel art inspirado en Tamagotchi, con un gato y un perrito.

## Jugar

Abre `index.html` en un navegador moderno. No necesita instalación, dependencias, servidor ni claves.

- Comida, higiene, felicidad y energía que cambian con el tiempo.
- Alimentar cuesta 5 monedas; bañar y dar cariño son gratuitos.
- Dormir recupera energía con el paso del tiempo; despierta a la mascota antes de jugar.
- Minijuego de 25 segundos: estrellas +3 monedas, piedras −3, mínimo cero.
- Control táctil, ratón o flechas del teclado.
- Nivel y progreso guardados en localStorage de este navegador.

Cambiar entre gato y perro cambia la apariencia; ambos comparten progreso en este prototipo.

## Estado

Prototipo estático. Las monedas son virtuales y no tienen valor monetario. No hay pagos, anuncios, retiradas, cuentas ni sincronización entre dispositivos. Todavía no está conectado a Telegram.

## Próximos pasos

1. Personalizar nombres, sprites y animaciones.
2. Crear el bot y configurar su Mini App con una URL HTTPS accesible para los jugadores.
3. Añadir backend, validación de identidad de Telegram y almacenamiento por jugador.
4. Validar puntuaciones y economía en el servidor antes de añadir premios o pagos.

No incluyas tokens del bot ni secretos en este repositorio público.

## Comprobación realizada

Sintaxis del JavaScript comprobada con Node.js. Pendiente prueba visual e interacción en navegadores y dentro de Telegram.

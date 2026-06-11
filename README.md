#feliz-mes

Una página web romántica sorpresa diseñada para celebrar un aniversario especial. Consta de cuatro pantallas: una entrada con nombre, una ruleta para elegir una actividad, un selector de hora y una pantalla final con los detalles del encuentro.

## Cómo funciona

1. La página se desbloquea cuando el destinatario escribe el nombre correcto.

2. Una ruleta ofrece seis opciones de actividades: cine, pickleball, cena, minigolf, karts y pintura.

3. El destinatario elige una hora (de 17:00 a 21:00).

4. Una pantalla final muestra el mensaje y los detalles del encuentro.

## Configuración

Sin dependencias. Simplemente abre `index.html` en un navegador.

Para personalizarla, edita las siguientes variables al principio de la etiqueta `<script>`:

```js
const UNLOCK_NAME = 'sam'; // Nombre para desbloquear la página (en minúsculas)
```

Coloca tu GIF en `assets/garu-pucca.gif` o actualiza la ruta `src` en la sección final de la página.

## Stack

HTML, CSS, JavaScript: un solo archivo, sin frameworks.

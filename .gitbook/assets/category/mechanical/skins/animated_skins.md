## Skins Animadas

by GodLander

<figure>
    <img src="/.gitbook/assets/img/preview/animated_skin.png" alt="">
    <figcaption>Ilustración del funcionamiento de la función Skin Animada</figcaption>
</figure>

### Pieles Animadas

Las pieles animadas son una emocionante característica que permite dar vida a la apariencia de tu personaje en el juego. Aquí hay algunos detalles clave sobre cómo funcionan:

#### Píxel de Control

El píxel superior central derecho (32, 0) de la piel actúa como el píxel de control. Para habilitar la animación, el valor alfa debe ser 234.

#### Control de Duración y Cuadros

Los valores R y G (en un rango de 0 a 255) controlan la duración en centésimas de segundo (0.1 seg) de cada cuadro de animación. Puedes ajustar estos valores para controlar la velocidad y duración de la animación, con un máximo de 25.5 segundos.

#### Interpolación

El valor B se utiliza para establecer la interpolación en la animación. Si el valor no es 0, la animación se interpolará, permitiendo transiciones suaves entre cuadros.

#### Cuadros de Animación

El primer cuadro muestra la apariencia normal de la piel del jugador. El segundo cuadro se almacena en un espacio generalmente no utilizado en la textura de la piel.

¡Explora la creatividad y da vida a tu piel con efectos visuales dinámicos y animaciones cautivadoras en el mundo del juego!

Esta herramienta proporciona una forma eficiente de trabajar en animaciones para la piel del jugador, permitiendo controlar la duración y la interpolación para crear efectos visuales más dinámicos.

Enlace de la herramienta Godlander: [Skin Animada](https://jsfiddle.net/Godlander/5sen7Lw1/137/)
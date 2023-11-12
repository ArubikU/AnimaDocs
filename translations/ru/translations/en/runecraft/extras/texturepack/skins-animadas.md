---
description: by GodLander
---

# Skins Animadas

![](<../../../.gitbook/assets/image (3) (1) (1).png>)

- Píxel superior central derecho (32, 0) de la piel es el píxel de control, el valor alfa debe ser 234 para habilitar la animación de la piel.
- Los valores R y G (de 255) controlan la duración en centésimas de segundo (0.1 seg) de cada cuadro, el máximo es de 25.5 segundos.
- El valor B se utiliza para establecer la interpolación. Si no es 0, la animación se interpolará.
- El primer cuadro es lo que normalmente se mostraría como la piel del jugador.
- El segundo cuadro se almacena en lo que normalmente es un espacio no utilizado en la textura de la piel.

Esta [herramienta](https://jsfiddle.net/Godlander/5sen7Lw1/137/) puede facilitar el trabajo

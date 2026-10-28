# De la foto de un plano a una casa en 3D que puedes recorrer

El prompt de **Claude Code** que convierte la foto del plano de una casa en un sitio 3D: entras por la puerta,
recorres cada cuarto, lo miras desde arriba y cambias la textura del sofá o del piso con un clic. Para decoración,
arquitectura y propiedades: en vez de un PDF sin vida, tu cliente ve de verdad cómo va a quedar.

Hecho por [Diego Osorio](https://instagram.com/soydiegoosorio).

**[👉 Guía paso a paso (instala Claude Code, copia el prompt y pégalo)](https://diegodoc1111.github.io/prompt-plano-3d/)**

## Qué hace

1. Lee la foto del plano y te muestra la lista de ambientes con sus medidas para que la apruebes.
2. Construye un solo archivo `casa3d.html` (Three.js desde CDN, abre con doble clic): paredes, puertas, ventanas, piso por
   ambiente, techo que se oculta, muebles según el uso de cada cuarto, carro en el garaje, patio.
3. Recorrido automático por todos los ambientes, modo libre (flechas / WASD + mouse) y vista de plano.
4. Nombre del ambiente al pasar el mouse y paleta de colores y texturas al hacer clic en muebles o piso.

## El prompt

Está en [`docs/prompt.txt`](docs/prompt.txt). Se usa desde Claude Code en una carpeta con la foto del plano.
No necesita skills ni programas extra.

## Fuentes verificadas

- Comandos de instalación de Claude Code: https://code.claude.com/docs/en/setup (28-oct-2026).
- Claude Code requiere plan Pro, Max, Team o Enterprise; el plan gratis no lo incluye (misma página).

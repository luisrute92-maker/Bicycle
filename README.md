# Slap Royale

Juego de cartas para dos jugadores: tú contra la máquina. Se reparten dos barajas (104 cartas) y gana quien se queda con todas.

Todo el juego está en un único `index.html`, sin dependencias. Se abre con doble clic en cualquier navegador.

Disponible en **español e inglés**: el juego empieza en inglés y el idioma se cambia con las banderas del menú principal.

## Reglas

- Por turnos, cada jugador lanza a ciegas la carta de arriba de su montón. Si tardas más de 5 segundos, se lanza sola.
- Las figuras obligan al rival a lanzar seguidas: **J = 4**, **Q = 3**, **K = 2**, **A = 1** cartas.
  - Si durante el castigo sale una figura, el castigo pasa al otro jugador.
  - Si no sale ninguna, quien lanzó la última figura se lleva el montón.
- **Bamboozle**: dos cartas seguidas del mismo valor. El primero en tocar la mesa se lleva el montón.
- **Sandwich**: dos cartas del mismo valor con una cualquiera en medio (7 – K – 7). También se gana tocando primero. Se puede desactivar en Opciones.
- **Toque falso**: si tocas sin que haya jugada, el rival se lleva el montón.
- Pierdes en cuanto te quedas sin cartas.

## Controles

| | Lanzar | Tocar la mesa |
|---|---|---|
| PC | Flecha arriba (↑) | Barra espaciadora (o clic en la mesa) |
| Móvil | Deslizar tu montón hacia arriba | Tocar la mesa |

`Esc` pausa la partida.

## Pruebas

Abre `index.html?test=1` para ejecutar las pruebas del motor del juego, incluida una simulación de 1000 partidas.

## Créditos

- Tipografías [DM Serif Display](https://fonts.google.com/specimen/DM+Serif+Display) y [Montserrat](https://fonts.google.com/specimen/Montserrat), bajo licencia SIL Open Font License, incrustadas en `index.html`.

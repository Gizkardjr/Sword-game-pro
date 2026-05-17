# Sword Game Pro

Juego 2D en HTML, CSS y JavaScript usando `<canvas>`.

## Estructura del proyecto

```text
Sword-game-pro/
├── index.html
├── style.css
├── game.js
├── README.md
└── audio/
    └── Battle_theme_loopable.mp3
```

## Archivos principales

- `index.html`: estructura del juego, menú, HUD, tienda, panel de información, canvas y audio.
- `style.css`: diseño visual del menú, HUD, paneles, botones, tienda y pantalla del juego.
- `game.js`: lógica del juego: jugador, enemigos, oleadas, jefes, portal, tienda, monedas, música, colisiones y controles.
- `audio/Battle_theme_loopable.mp3`: música principal del juego.

## Cómo jugar

1. Abre `index.html` en el navegador.
2. Presiona **JUGAR**.
3. Usa los controles del teclado.

## Controles

```text
WASD = moverte
ESPACIO = atacar o cargar ataque
P = pausa
I = información
Q = invocar gato desde ronda 10
1 = mejorar fuerza
2 = mejorar velocidad
3 = mejorar vida
4 = mejorar gato
H = invocar helicóptero si está equipado
E = poder especial de algunos personajes
```

## Mecánicas principales

- Ganas monedas derrotando enemigos y completando rondas.
- Cada 10 rondas aparece un jefe.
- Al derrotar un jefe aparece un portal.
- Entra al portal para avanzar al siguiente mapa.
- Las mejoras y desbloqueos se muestran en el HUD superior.

## Mapas

```text
Rondas 1-10 = Bosque Oscuro
Rondas 11-20 = Volcán de Lava
Rondas 21-30 = Reino Helado
Rondas 31-40 = Desierto Dorado
Rondas 41-50 = Pantano Venenoso
Rondas 51-60 = Ciudad Sombría
Rondas 61-70 = Templo Celestial
Ronda 71 en adelante = Abismo Final
```

## Publicación en GitHub Pages

Para publicar el juego, el repositorio debe tener `index.html` en la raíz. Después activa GitHub Pages desde la configuración del repositorio.

## Notas de desarrollo

- No cambies rutas de audio sin actualizar `index.html`.
- Haz cambios grandes en ramas separadas.
- Prueba el juego antes de hacer `commit` y `push`.


## Obstáculos reales

En esta versión, varias decoraciones del mapa ya funcionan como obstáculos:

- Árboles
- Piedras y rocas
- Cactus
- Cristales
- Pilares, estatuas y ruinas
- Cajas y troncos

El jugador, enemigos y mascota no pueden atravesarlos. Los proyectiles normales también se detienen cuando chocan con estos objetos.

[¿mejor configuracion los lerps?](https://github.com/DanteMRX/Left-4-Dead-2-Configuraciones-y-Comandos/blob/main/Configuraci%C3%B3n%20de%20Lerps.md)



# Guia de Ayuda para Left 4 Dead 2 

Esta guía busca ayudar y optimizar el juego para que tengas una mejor experiencia

## Comandos Basicos para el juego📋

Lo primero que se debe de hacer es activar la consola colocando en "parametros del juego"

```
-console
```
Entrar al juego y bindear el siguiente comando:

```
Bind f10 "toggleconsole"
```
 > Abre la consola desde la tecla asignada (F10).

```
Net_Graph 1
``` 
> Muestra estadísticas como FPS y latencia en pantalla.

```
Bind f11 "disconnect"
```
> Desconéctate rápidamente de un servidor con (F11).

```
sv_consistency 0
```

> [!IMPORTANT]\
> _Siempre escribe este comando `sv_consistency 0`en la consola o un archivo autoexec.cfg para evitar que los jugadores sean expulsados por el uso de mods en servidor local. *esta incluido en el autoexec.cfg para que se ejecuque al iniciar el juego*_

## Configuración mejorada para (parametros del juegos)

Estos comandos ayudaran a mejorar y optimizar 
factores en el juego

```
-high -nosync -nomsaa -noaafonts -lv -nojoy -novid -console -freq (Hz of your monitor) -useallavailablecores -nod3d9ex -dxlevel 81 -threads (Cores of your processor)
```
## Configuración Recomendada para fps y Ping
```
-high -refresh 60 -nojoy -novid -console -lv
```

## Descripción de los comandos:🗒

`-high`: Asigna una prioridad alta al proceso del juego.

`-nosync`: Desactiva la sincronización vertical, mejorando la velocidad de fotogramas.

`-nomsaa`: Desactiva el Multi-Sample #Anti-Aliasing (MSAA).

`-noaafonts`: Desactiva el antialiasing de fuentes.

`-lv`: Reduce la violencia gráfica.

`-nojoy`: Desactiva el soporte para joysticks o gamepads.

`-novid`: Omite el vídeo de introducción del juego.

`-console`: Habilita la consola de comandos en el juego.

`-freq`: Especifica la frecuencia de actualización del monitor en hercios (Hz).

`-useallavailablecores`: Utiliza todos los núcleos disponibles del procesador.

`-nod3d9ex`: Desactiva características de DirectX 9Ex.

`-dxlevel 81`: Configura el uso de DirectX 8.1.

`-threads`: Especifica el número de hilos de procesamiento que el juego utilizará.


## Comandos Útiles para la partida📓

`status` _se usa en la consola para mostrar información sobre los jugadores conectados al servidor, como sus IDs, nombres y direcciones IP._

`kick <nombre del jugador>` 
> _se usa para expulsar a un jugador de tu servidor local_

`setinfo name <nombre del jugador>` 

> _cambiar el nombre dentro de la partida_

`bind <letra asignada> say_team "TANK GO BACK!"` 
> _envia un mensaje rapido solo para tu equipo_

`bind <letra asignada> say "!ready"` 

> _envia un mensaje para todo el chat global_ 


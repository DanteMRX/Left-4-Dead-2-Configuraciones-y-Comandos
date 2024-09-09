
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


## Comandos para el crosshair📌: 

|Nombre_de_la_cvar |valor predeterminado |Rango de valores disponibles|
| :---         |     :---:      |          ---: 
| crosshair         	  | "1"    |0 - 1 |
| cl_crosshair_alpha   | "255"  |0 - 255|
| cl_crosshair_dynamic | "1"    |0 - 1  |
|cl_crosshair_thickness| "2"    |0 - 5  |
| cl_crosshair_red    | "138"  |0 - 255 RGB|
| cl_crosshair_green | "182"  |0 - 255 RGB|
|cl_crosshair_blue   | "220"  |0 - 255 RGB|

`crosshair 0/1`:
 > activar y desactivar la mira en el juego

`cl_crosshair_alpha 255`
> Ajusta la opacidad del punto de mira (crosshair). El valor 255 significa completado`

`Cl_Crosshair_Dynamic 0`: 
> Deja la mira estática para mejorar la precisión al disparar.

`cl_crosshair_dynamic 1` 
> Activa un punto de mira dinámico. Esto hace que el punto de mira se expanda cuando te mueves y se reduzca cuando te quedas quieto, lo que te ayuda a medir mejor la precisión en movimiento.

`cl_crosshair_thickness 2` 
> Controla el grosor de las líneas del punto de mira. Un valor de 2 significa que las líneas serán más gruesas.

`cl_crosshair_red 255` 

> Define el valor del componente rojo en el color del punto de mira. El valor 255 significa el máximo nivel de rojo.

`cl_crosshair_blue 255` 
> Define el valor del componente azul en el color del punto de mira. El valor 255 significa el máximo nivel de azul.

`cl_crosshair_green 255` 

> Define el valor del componente verde en el color del punto de mira. El valor 255 significa el máximo nivel de verde.

### comando adicional 🖇

```
cl_colorblind 0
``` 
> [!TIP]
> Activa o desactiva el modo para daltónicos. Un valor de 0 significa que está desactivado, lo que significa que el juego no aplicará filtros de color para ayudar a los jugadores con deficiencias de visión de color.

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


## Configuración de Lerps (Latencia)

## Valores por defecto:
`cl_cmdrate 100`
`cl_updaterate 60`
`cl_interp_ratio 2`
`cl_inter 0.1000000`

## Los Peores:

`cl_cmdrate "30"`
`cl_updaterate "20"`
`cl_interp_ratio "-1"`
`cl_interp "0.0333"`
`rate "30000"`

## Intermedios:
`cl_cmdrate "60"`
`cl_updaterate "60"`
`cl_interp_ratio "1"`
`cl_interp "0.067"`
`rate "60000"`

## Los Mejores:
`cl_cmdrate "100"`
`cl_updaterate "100"`
`cl_interp_ratio "1"`
`cl_interp "0.000"` 
`rate "100000"`

## Los Mejores (Para usar esta configuracion el juego tiene que ir a más de 150 FPS) *sino no veras gran cambio*
`cl_cmdrate "128"`
`cl_updaterate "128"`
`cl_interp_ratio "1"`
`cl_interp "0.000"`
`rate "128000"`

## Mi configuracion
`cl_cmdrate 128`
`cl_updaterate 128`
`cl_interp_ratio 0`
`cl_interp 0.0167`

## Tener el mejor ping disponible
`cl_cmdrate 10`
`cl_updaterate 10`
`cl_interp_ratio 0`
`cl_interp 0.0300` (va de 0.1000 - .0001)

## Comandos Útiles para la partida📓

`status` _se usa en la consola para mostrar información sobre los jugadores conectados al servidor, como sus IDs, nombres y direcciones IP._

`kick <nombre del jugador>` _se usa para expulsar a un jugador de tu servidor local_

`setinfo name <nombre del jugador>` _cambiar el nombre dentro de la partida_

`bind <letra asignada> say_team "TANK GO BACK!"` _envia un mensaje rapido solo para tu equipo_

`bind <letra asignada> say "!ready"` _envia un mensaje para todo el chat global_ 

### Silenciar el audio de jugadores

Lo primero que se debe de hacer es ir a la consola y colocar el comando 

```
voice_show_mute
```

despues nos aparecerá una lista en orden de los jugadores de la partida. colocaremos el siguiente comando con el numero del jugador al que queremos silenciar 

```
voice_mute <numero del jugador> 
```









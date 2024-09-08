## Optimización y Opciones de Lanzamiento del Juego (parametros del juegos)

-high -nosync -nomsaa -noaafonts -lv -nojoy -novid -console -freq (Hz of your monitor) -useallavailablecores -nod3d9ex -dxlevel 81 -threads (Cores of your processor)

## Configuración Recomendada para fps y Ping

-high -refresh 60 -nojoy -novid -console -lv

## Descripción de los comandos:

`-high`: Asigna una prioridad alta al proceso del juego.

`-nosync`: Desactiva la sincronización vertical, mejorando la velocidad de fotogramas.

`-nomsaa`: Desactiva el Multi-Sample Anti-Aliasing (MSAA).

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

## Comandos Basicos para el juego:

`Bind f10 "toggleconsole"`: Abre la consola desde la tecla asignada (F10).

`Net_Graph 1`: Muestra estadísticas como FPS y latencia en pantalla.

`Bind f11 "disconnect"`: Desconéctate rápidamente de un servidor con (F11).

`sv_consistency 0` Siempre escribe este comando en la consola o un archivo autoexec.cfg para evitar que los jugadores sean expulsados por el uso de mods en servidor local. *esta incluido en el autoexec.cfg para que se ejecuque al iniciar el juego*


## Comandos para Crosshair:

`Cl_Crosshair_Dynamic 0`: Deja la mira estática para mejorar la precisión al disparar.

`Cl_Viewmodelfovsurvivor 90`: Aumenta la distancia de tu arma en pantalla.

### Todos los comandos (por defecto):

`cl_crosshair_dynamic 1` Activa un punto de mira dinámico. Esto hace que el punto de mira se expanda cuando te mueves y se reduzca cuando te quedas quieto, lo que te ayuda a medir mejor la precisión en movimiento.

`cl_crosshair_alpha 255` Ajusta la opacidad del punto de mira (crosshair). El valor 255 significa completado.

`cl_crosshair_thickness 2` Controla el grosor de las líneas del punto de mira. Un valor de 2 significa que las líneas serán más gruesas.

`cl_crosshair_red 255` Define el valor del componente rojo en el color del punto de mira. El valor 255 significa el máximo nivel de rojo.

`cl_crosshair_blue 255` Define el valor del componente azul en el color del punto de mira. El valor 255 significa el máximo nivel de azul.

`cl_crosshair_green 255` Define el valor del componente verde en el color del punto de mira. El valor 255 significa el máximo nivel de verde.

`cl_colorblind 0` Activa o desactiva el modo para daltónicos. Un valor de 0 significa que está desactivado, lo que significa que el juego no aplicará filtros de color para ayudar a los jugadores con deficiencias de visión de color.


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

## tener el mejor ping disponible
`cl_cmdrate 10`
`cl_updaterate 10`
`cl_interp_ratio 0`
`cl_interp 0.0300` (va de 0.1000 - .0001)








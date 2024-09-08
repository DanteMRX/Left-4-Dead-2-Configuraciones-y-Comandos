## Optimización y Opciones de Lanzamiento del Juego (parametros del juegos)

-high -nosync -nomsaa -noaafonts -lv -nojoy -novid -console -freq (Hz of your monitor) -useallavailablecores -nod3d9ex -dxlevel 81 -threads (Cores of your processor)

## Configuración Recomendada para fps

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

## Comandos Adicionales:

`Bind f11 toggleconsole`: Abre la consola desde la tecla asignada (F11).

`Cl_Crosshair_Dynamic 0`: Deja la mira estática para mejorar la precisión al disparar.

`Cl_Viewmodelfovsurvivor 90`: Aumenta la distancia de tu arma en pantalla.

`Net_Graph 1`: Muestra estadísticas como FPS y latencia en pantalla.

`Bind f10 disconnect`: Desconéctate rápidamente de un servidor con F10.

## Configuración de Lerps (Latencia)

## Los Peores:

`rate "30000"`
`cl_cmdrate "30"`
`cl_updaterate "20"`
`cl_interp_ratio "-1"`
`cl_interp "0.0333"`

## Intermedios:
`rate "60000"`
`cl_cmdrate "60"`
`cl_updaterate "60"`
`cl_interp_ratio "1"`
`cl_interp "0.067"`

## Los Mejores:
`rate "100000"`
`cl_cmdrate "100"`
`cl_updaterate "100"`
`cl_interp_ratio "1"`
`cl_interp "0.000"` 

## Los Mejores (Para usar esta configuracion el juego tiene que ir a más de 150 FPS) *sino no veras gran cambio*
`rate "128000"`
`cl_cmdrate "128"`
`cl_updaterate "128"`
`cl_interp_ratio "1"`
`cl_interp "0.000"`







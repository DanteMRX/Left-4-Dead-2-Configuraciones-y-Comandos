## Configuración de Lerps (Latencia)

Cuando hablamos de LERP nos estamos refiriendo a lo que comúnmente se llama interpolación. La interpolación se introdujo en L4D2 para lograr que las animaciones del juego fueran fluidas, aun teniendo una mala conexión a internet.

Cuando nos conectamos a un servidor, nos comunicamos con él, y él con nosotros, es decir, nos intercambiamos paquetes. En los paquetes que enviamos va toda nuestra información de jugador en ese preciso momento.Todos los jugadores envían esos paquetes al servidor para informarle de lo que están haciendo. El servidor los recibe y los interpreta para crear lo que se conoce como el estado actual REAL de la partida. Que para que me entendáis, es como una foto de lo que está ocurriendo en ese preciso momento. 


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

Los servidores de L4D2 pueden realizar esta operación de actualización un máximo de 30 veces por segundo  que es lo que se conoce como 30 TICK. Que por cierto, es un valor bastante bajo si lo comparamos con los 64 TICK que suelen tener los servidores de CSGO, o los 128 TICK que suelen tener los servidores competitivos de este mismo juego.

Cuando el servidor crea esa, entre comillas, “fotografia” de la que estamos hablando, se la envía a los clientes (que somos nosotros los jugadores) para que se reproduzca en nuestras pantallas.
Aunque esta operación se realiza varias veces por segundo, el problema es que sigue sin ser lo suficientemente rápido como para reproducir el juego de una manera fluida.

Lo que hace la interpolación es crear una animación a partir del último paquete que hemos recibido. 

¿Cuánto tiempo es eso? Pues depende de nuestro LERP.
Por defecto, el juego tiene puesto el LERP a 100, lo que significa que tarda 100ms, pero a ese retardo habría que sumarle el ping de nuestra conexión a internet. Si ponemos como ejemplo que tenemos un ping de 50, quiere decir que todo lo que se nos muestra en pantalla mientras estamos jugando sucedió realmente hace 150ms.

Por lo tanto, cuanto más bajo sea el LERP, más fiel a la realidad será lo que estamos viendo en pantalla, pero menos fluido el irá el juego. 

Como ya hemos dicho, el valor por defecto del lerp es de 100, pero puedes cambiarlo por el que quieras, siempre que esté comprendido entre 0 y 500.
Normalmente poner un lerp por encima de 100 suele significar que eres idiota o que tienes malas intenciones, por lo que muchos servidores te kickearán al hacerlo.Entre los valores por debajo de 100 hay muchas opciones. 

Si no os gusta estar cambiando de LERP todo el rato o tenéis dudas al respecto, lo mejor es usar siempre el que os resulte más cómodo como superviviente.
Para cambiar el LERP se usan 2 comandos de consola por lo que si no sabéis como sacarla, echadle un ojo a este otro vídeo.

Dichos comandos son:
El cl_interp_ratio
Y el cl_interp
Pero antes conviene conocer estos otros 2:
Cl_cmdrate
Cl_updaterate
El cmdrate es el máximo de paquetes que puedes enviar al servidor por segundo. Nunca pongáis un valor mayor que la media de tus FPS.
El update rate es el máximo de paquetes que se puede recibir del servidor

Y por último, tenemos el cl_interp que es donde decidimos que tipo de lerp queremos ponernos. Recordad que por defecto está a 100, por lo que lo suyo es poner cifras por debajo de ese valor.
Algunos ejemplos populares son 10, 16.7, 20, 33, 38, 40, 50 o 67.

Si no sabéis con cual quedaros, empezar por un valor bajo, probad el 16.7, y si veis que las animaciones son demasiado bruscas para vosotros, id subiendo hasta encontrar el que más os guste. 
Por cierto, se pone de manera decimal, así que si por ejemplo quisierais usar el 16.7, deberíais poner:

Cl_interp 0.0167
Lo mismo con el resto.
Si queréis saber los valores que tenéis puestos, usad el comando net_graph 1

> [!NOTE]
> Toda la información presentada ha sido recopilada a partir del contenido proporcionado por el canal de Val, el cual ha sido una fuente confiable y detallada para la elaboración de este material. El análisis y los datos utilizados han sido extraídos de los recursos ofrecidos en dicho canal, asegurando así la precisión y relevancia de la información aquí expuesta.









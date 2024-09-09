## Comandos para el crosshair📌: 

### Definición:
El Crosshair o Punto de mira es un conjunto de dos líneas que se cruzan en ángulo recto y se colocan superpuestos en el campo de visión de una pantalla, usado generalmente para los Juegos First Person Shooter como (CSGO, TF2, HL,L) En este caso la saga de Left 4 Dead.

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
> Nuestra mira se pondrá de color blanco con un borde negro. Lo malo es que no se puede modificar el grosor del borde. Además cuando tenemos esta opción puesta no podemos elegir ningún otro color, por lo tanto si queréis tener de nuevo una mira con color, deberéis poner este comando a 0.

> [!TIP]
> Activa o desactiva el modo para daltónicos. Un valor de 0 significa que está desactivado, lo que significa que el juego no aplicará filtros de color para ayudar a los jugadores con deficiencias de visión de color.

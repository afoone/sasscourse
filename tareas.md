# NESTING

## Tarea 1

- Crear un *div* en el html, de clase quote. Dentro del él un *header 1* y un *p*.
- El *header* servirá para tener el autor de una cita y el p para la cita en sí.
- El header ha de estar en color *darkgrey* y en tamaño 0.9 em, el p estará en cursiva.
- Siempre usando nesting. Usar también anidamiento de propiedades en la fuente.

## Tarea 2

- Las frases de quote han de ir centradas (las dos).
- Convertir el título en un enlace hacia la wikipedia del autor
- El enlace debe mantener el darkgrey, escepto cuando el ratón pase por encima, que ha de estar en otro tono de gris.
- El enlace se ha de abrir en una pestaña nueva

## Tarea 3
- Personalización completa de la fuente del autor: 
  -  Fuente: 'Lucida Sans', Verdana, sans-serif;
  -  Tamaño: 1.5em;
  -  Variante: small-caps;
  -  Weight: 600;
- Caja con sombreado. Se puede usar https://www.cssmatic.com/box-shadow 
- Padding y margin de al menos 1em
- Un color de fondo


# VARIABLES

 ## Tarea 4
 - Poner todos los colores, las fuentes, el formato de sombra en variables, los padding y los margin
 - Fijarse en que hay variables de listas y de string
 - Probar a cambiar valores

 ## Tarea 5
 - Usar un mapa para almacenar los valores de padding y margin en la variable quote_spaces(key: value, key: value)
 - Para recuperarlos hay que usar la función map_get

# MIXINS

## Tarea 6
 - Añadiremos dos botones al elemento de clase *quote*
 - Uno será "Me gusta" y el otro "No me gusta"
 - Las clases serán *btn-like* y *btn-dislike*
 - Seran de color de texto blanco, ancho 130px , altura 40px, radio del borde 10px.
 - El de me gusta será de color verde y el de no me gusta de color rojo
 - Crearlo SIN mixins

## Tarea 7 
 - Crear un mixin para las clases de botones anteriores, con todas las propiedades comunes
 - Probar sobreescribir alguna propiedad del mixin, por ejemplo el color de fuente

## Tarea 8
 - Establecer la fuente en el mixin (con anidamiento de propiedades)
 - En especial , que sea bold y la familia (¿Verdana?)

## Tarea 9
 - Pasar por parámetro el border radious (20px)
 - Pasar por parámetro el color de fuente
 - Probar colores
 - Establecer valor por defecto el color de fuente
 - Dejar de pasar el color de fuente en el include

## Tarea 10
 - Crear un mixin para el shadow, se le pasará el parámetro tipo lista
 - Pensar en la utilidad de este último mixin

 # FUNCIONES

## Tarea 11
 - Hacer una función que calcule proporcionalmente el valor del alto en base al ancho que le pasemos y usarla para que nuestros botones siempre tengan la misma proporción sin necesidad de establecer más que el ancho del botón.
 - Poner el width en una variable
 - Cambiar el tamaño (width) a 180px para probar

## Tarea 12 
 - Hacer otra función para que el botón siempre sea de borde redondo (radio la mitad de la altura), cambiando el mixin para que acepte tan sólo el ancho y ya haga todo lo demás



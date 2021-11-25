# Estándar de codificación

## Diseño del código

Usa 1 (un) espacio por indentación. Este es el predeterminado trabajando en la herramienta replit.


## Importaciones

Más de una importación puede estar en la misma línea que otra.

Las importaciones se realizan en este orden basado en su importancia:
- Importaciones que son vitales para el funcionamiento del bot.
- Importación de la base de datos, si es que se utiliza.
- Importación de clases.
- Importación de funciones locales.


## Espacios en blanco

Se pueden dejar líneas de código para diferenciar el comienzo de un proceso con el fin de otro. 

Los espacios en blanco innecesarios en sentencias deben tratar de omitirse a toda costa.


## Uso de funciones

Si un bloque de código ocupa al menos 20 sentencias distintas. Debe considerarse profundamente el uso de funciones. Para el caso del archivo principal 'main' sí o sí llegadas las 20 líneas de código se debe agrupar en una función.


## Uso de clases

Considerar el uso de clases para agrupar funciones que trabajen de la misma forma ya sea en otras partes del código suelto o incluso en otras clases.


## Demasiado texto

Todo el texto que se utilice como una constante debe ser almacenado en la base de datos.


## Uso de la base de datos

En caso de tener texto constante este debe ser almacenado en la base de datos.

Antes de eliminar algún elemento de la base de datos se debe compilar el código imprimiendo las keys, tras esto se debe hacer una segunda compilación pero esta vez usando directamente la key que se busca eliminar. Esto para comprobar su contenido.

Si se tienen variables que son constantes se almacenan en la base de datos. 


## Cambios en el código

Antes de realizar un cambio es importante que se notifique al resto del equipo. Pero hablando del estándar propuesto para esto, al realizar un cambio se comenta sobre el comienzo del cambio el autor de dicho cambio así como la fecha. 

En caso de cambiar grandes cantidades de código respaldar el código antiguo en un archvo.py.

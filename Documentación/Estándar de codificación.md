# Estándar de codificación

## Diseño del código

Usa 1 (un) espacio por indentación. Este es el predeterminado trabajando en la herramienta replit.

Evitar la acumulación de sentencias 'if'. En caso de tener algún código de la forma 'if - elif - ... - elif - else' o 'if; if; if; if; else' este debe ser reemplazado por alternativas como el uso de ciclos for con el manejo de listas. 

Para el nombramiento de funciones, variables, keys y otros que lo ameriten. Se utilizará la el camelCase.

Para el caso de las funciones los nombres de estas deben corresponder a verbos, el idioma de estos puede variar.

Para el caso de las clases los nombres de estas deben corresponder a sustantivos, el idioma de estos debe ser en español.

Se puede alternar entre el uso del español e inglés en el código, esto para solventar los problemas que puede tener utilizar caracteres especiales como la 'ñ'


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


## Texto

Todo el texto que se utilice como una constante debe ser almacenado en la base de datos.


## Uso de la base de datos

En caso de tener texto constante este debe ser almacenado en la base de datos.

Antes de eliminar algún elemento de la base de datos se debe compilar el código imprimiendo las keys, tras esto se debe hacer una segunda compilación pero esta vez usando directamente la key que se busca eliminar. Esto para comprobar su contenido.

Si se tienen 'variables' que son constantes (como los diccionarios o listas) se almacenan en la base de datos. 


## Cambios en el código

Antes de realizar un cambio es importante que se notifique al resto del equipo. Pero hablando del estándar propuesto para esto, al realizar un cambio se comenta sobre el comienzo del cambio el autor de dicho cambio así como la fecha. 

En caso de cambiar grandes cantidades de código respaldar el código antiguo en un archvo.py.

Al terminar una 'jornada' de trabajo en el código, asegurarse que este siga funcionando, con esto se refiere a que el código siga compilando.

Si se desea actualizar el repositorio del código al realizar cambios, estos deben ser sustanciales. Los suficientes para que se pueda considerar que es otra versión del bot.

## Uso de comentarios

Los comentarios deben tener una duración máxima de dos días. Tras esto son eliminados para tener más limpieza en el código.

Se hacen comentarios en estas situaciones:
- El bloque de código que sigue al comentario es complejo y su comprensión no es intiutiva.
- Se realizaron cambios importantes a bloques de código.
- Se da por concluido algún proceso importante, por lo que a priori no va a recibir más cambios.

# juegos con HTMLS

## Elementos Canvas

- El elemento canvas, junto al lenguaje JS nos permite crear animaciones y juegos 2d en el navegador.

- En el navegador el código se interpreta de manera secuencial

- para utilizar el código JS, debemos esperarar a que todos los elementos HTML hayan sido creados antes de ser utilizados.

- Alternativas:
    - Colocar el script en la parte inferior de la página.
    - Utilizar un detector de eventos que nos indique cuando los elementos han sido creados. (evento onload desde el body o script)

- se crea una variable canvas por medio del identificador de la etiqueta
- se verifica si la variable se creó correctamente
- en realidad se trabaja con el **conexto** de canvas 2d, se crea una variable **ctx** con la cual se manipula el canvas.
- se verifica que el contexto se haya creado de manera exitosa, dando la bienvenida por medo de un alert(), o advirtiendo un error de creacion de contexto
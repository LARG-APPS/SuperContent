CSS (Cascading Style Sheets) hojas de estilo en cascada es 
un lenguaje para darle estilo, presentación o diseño a las 
páginas web

HTML define la estructura y el contenido de las páginas web
En HTML no debemos hacer nada para cambiar el estilo de la página, 
eso lo debemos hacer con CSS para tener todos los estilos en un 
solo lugar (si luego quisieramos cambiar todos los estilos solo 
cambiamos el CSS y listo, no nos demoraría ir por cada .html)

En este curso usaremos Brackets.io como editor de código
Podríamos usar Sublime Text, Notepad++ o incluso el 
Blog de notas de windows

En Brackets seleccionamos "Abrir carpeta" y seleccionamos
la carpeta en la que vamos a estar trabajando nuestro proyecto

Los estilos CSS se escriben en archivos con la extención .css

Para agregar estilos CSS a nuestra página web tenemos tres 
opciónes;
1. Enlazar una hoja de estilos externa: para eso colocamos `<link rel="stylesheet" href="./ruta/de/estilos.css">` en el head
2. Escribir reglas CSS dentro del elemento style (que va dentro de head): `<style type="text/css"> /*Your CSS rules here*/ </style>`
3. Escribir propiedades CSS (con sus respectivos valores) en cualquier elemento HTML dentro del atributo `style` (este es un atributo global y se puede usar en cualquier etiqueta HTML): `style="background: red;"`

La primera opción es la más recomendada para sitios web grandes, 
porque es muy buena para reutilizar el código CSS
La segunda forma es menos recomendada, pero es más fácil de 
usar para aplicar estilos a una sola página web
Y la tercera es la forma menos recomendada de agregar estilos a 
una página web, porque los estilos solo se aplicarán a un elemento
HTML y no se pueden reutilizar

Los selectores seleccionan elementos html para aplicarles los 
estilos

Los archivos CSS estan compuestos de reglas CSS, una regla CSS 
se vé de la siguiente manera

~~~
selector {
  propiedad: valor;
}
~~~

Los colores en CSS
RGB van desde el 0 hasta el F (0123456789ABCDEF)
Tambien se pueden usar colores literales, 
es decir el nombre del color en inglés (red, green, pink, etc)

Selectores

* es el selector universal, elige absolutamente todos los 
elementos HTML

Selector de etiquetas, es el nombre de la etiqueta y selecciona 
todas las etiquetas del mismo tipo


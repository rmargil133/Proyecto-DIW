3.2 Debemos añadir dos formas de incluir estilos en el CSS de forma directa y explicar si es
recomendable su uso. (se puede añadir un documento readme.txt en el proyecto, o en un
comentario)

La dos posibles formas son o bien linkeando un archivo separado del html mediante la siguiente sintaxis:

<link rel="stylesheet" href="RUTA ARCHIVO" />

o bien metemos el codigo del css en el mismo html dentro del head creamos una etiqueta (<style></style>) y dentro de esa etiqueta style metemos el codigo css.

Esta segunda manera no es muy recomendable, la pricnipal razón es porque si se quiere hacer una modificación en los estilos definidos, es necesario modificar 
todas las páginas que incluyen el estilo que se va a modificar.

Siempre es mas recomendable linkear el archivo css separado del html

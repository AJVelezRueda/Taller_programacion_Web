# *PROGRAMACI脫N WEB* 
## UNA BREVE INTRODUCCI脫N...

> 馃毃 WARNING: este tutorial hace un recorrido muy breve sobre los lenguajes web, te invito a no quedarte solo con este recorrido y a animarte a explorar el basto mundo de la programaci贸n Web

# Guias de Trabajo
* [1. Internet](#1-interntet)
* [2. Web](#2-Web)
* [3. Directo al hueso de las p谩ginas](#3-html)
* [4. Las cosas por su nombre](#4-semantica)

[1. Internet](#1-interntet)

Internet se podr铆a definir como la red de redes de computadoras, conectadas por medio de un cableado f铆sico que permite intercambiar informaci贸n entre todos sus usuarios. 

Para acceder al servicio que ofrece la informaci贸n, debemos tener dos programas que se ejecutan en dos computadoras diferentes y que nos permiten compartir recursos. 

A la computadora que ejecuta el programa que proporciona el recurso o informaci贸n se la denomina **servidor** y a la computadora que consume un recurso o informaci贸n se la denomina **cliente**. En la computadora del cliente se ejecutar谩 entonces el programa que le permite utilizar el recurso o leer la informaci贸n.

Pero 驴Qu茅 tipo de recursos pueden brindarse o consimirse a trav茅s de internet? Por medio de Internet podemos enviar mensajes, programas ejecutables, archivos de texto, consultar bases de datos, etc.

[2. La Web](#2-web)
La Web en particular, diminutivo de World Wide Web, es un conjunto de p谩ginas interconectadas por las cuales podemos navegar.

Estas p谩ginas web est谩n pensadas para consumir contenido hipertextual, es decir  contenido que contiene v铆nculos o enlaces a otros contenidos.


[3. Directo al hueso de las p谩ginas](#3-html)
HTML es un tipo de lenguaje que define la estructura o el esqueleto de algo mediante la codificaci贸n de informaci贸n para que la informaci贸n pueda ser representada de una forma adecuada.

HTML es un acr贸nimo de Hyper Text Markup Language, o lo que es lo mismo, Lenguaje de Marcado de Hyper Texto.

El Hyper Texto tampoco es s贸lo texto鈥? Entre los elementos del hiper texto podemos encontrar videos, im谩genes, sonidos, etc.

La sintaxis HTML se basa en etiquetas, que son las que le permite al browser (el programa que permite visualizar este tipo de archivos) interpretar como mostrar el contenido.
Las etiquetas se escriben entre <> 
Las etiquetas generalmente delimitan el contenido que est谩n identificando y se deben abrir `<etiqueta>` y cerrar luego de escribir el contenido agregando a la misma etiqueta una barra invertida `</etiqueta>`

```html
<html>
		contenido
</html>

```
Algunas etiquetas no tienen etiqueta de cierre con la barra invertida, son 煤nicas:

```html
<img src="images/las_de_sistemas.png" alt=鈥濃??>
```

Existen, adem谩s, atributos para las etiquetas que le agregan una funcionalidad extra a la etiqueta que lo contiene:

```html
<p style="font-size: 18px;"> Este es mi texto con estilo propio</p>
```

Un documento HTML est谩 formado por partes:

- Una l铆nea que contiene informaci贸n sobre la versi贸n de HTML (no siempre),

- Una cabecera (delimitada por el elemento HEAD)

- Un cuerpo, con el contenido del documento (delimitado por el elemento BODY).

Todo el documento tiene que ir entre las etiquetas `<html></html>` e inicia con la etiqueta `<!DOCTYPE html>`

La etiqueta `<head>` contiene informaci贸n sobre el documento actual, como el t铆tulo, palabras clave que utilizan los motores de b煤squeda, y otros datos que no se consideran parte del contenido del documento porque no se visualizan en el navegador. 
La etiqueta `<body>` contendr谩 el contenido particular de esta p谩gina.

> 馃憠驴Te animas a buscar qu茅 otras etiquetas existen y para qu茅 sirve?
>
> 馃馃徎鈥嶁檧锔?**Desaf铆o**: Cre谩 un archivo de texto con la herramienta que tengamos a mano (visual code, editor de texto, bloc de notas,etc) y lo guardamos con el nombre 鈥渕i_pagina鈥? con extensi贸n 鈥?.html鈥? : 鈥渕i_cv.html鈥?
>
>Iniciamos el documento con las etiquetas como sigue:
>
```html
<!DOCTYPE html>
<head>
 		<meta charset="UTF-8">
		<title>Document</title>
</head>
<body>
</body>
</html>
```
>


[4. Las cosas por su nombre](#4-semantica)
La sem谩ntica hace referencia al significado de las palabras y al significado de las oraciones. HTML nos brinda etiquetas para reforzar el significado de la informaci贸n de 
nuestra p谩gina web

El HTML sem谩ntico no se trata s贸lo de utilizar las nuevas etiquetas sem谩nticas, sino de utilizar las etiquetas correctas para cada elemento o secci贸n de tu p谩gina web, para que sea f谩cil de navegar para todos los usuarios

Algunas de las etiquetas sem谩nticas m谩s usadas son:

- `<section></section>`

- `<figure></figure>`

> 馃憠 驴Qu茅 otras etiquetas sem谩nticas podes encontrar?

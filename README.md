# Markdown
Resumen del curso Markdown de Linkedin

## ¿Qué es Markdown?
Markdown es un formato de enmarcación de texto, que permite crear texto con formato. Markdown es utilizado en los archivos llamado ***README.md***, los cuales se encuentran en cualquier proyecto de Software, y son utilizados para dar una pequeña descripción de lo que consiste dicho proyecto.

Es un lenguaje de marcado ligero creado por John Gruber que trata de conseguir la máxima legibilidad y facilidad de publicación tanto en su forma de entrada como de salida, inspirándose en muchas convenciones existentes para marcar mensajes de correo electrónico usando texto plano. Se distribuye bajo licencia BSD y se distribuye como plugin (o al menos está disponible) en diferentes sistemas de gestión de contenidos (CMS). Markdown convierte el texto marcado en documentos XHTML utilizando html2text creado por Aaron Swartz. Markdown fue implementado originariamente en Perl por Gruber, pero desde entonces ha sido traducido a multitud de lenguajes de programación, incluyendo PHP, Python, Ruby, Java y Common Lisp.


# ¿Para qué se usa Markdown?
Algunas de las opciones con las que te será más fácil la vida usando Markdown:
* Redacción de correos electrónicos:  es perfecto para escribir correos electrónicos que necesiten tener un formato especial de forma cómoda y rápida.
* Listas de tareas pendientes: perfecto también para aquellas listas de tareas con texto sin formato. Incluso si se desea utilizar una aplicación especializada, como Cheddar para iOS, este también admite Markdown.
* Notas organizadas: similar a las listas de “to do” anteriores, la mayor parte de las aplicaciones para tomar notas son compatibles con Markdown, siendo fácil su organización sin necesidad de tocar el formato.


## MarkDown Básico
### Cabeceras
* MarkDown nos permite escribir cabeceras de la siguiente manera:
Con el signo ***===*** podemos crear cabeceras de primer nivel (títulos), esto relacionado con HTML, es como crear un H1

~~~
Cabecera 1
==========
~~~

* Con el signo ***---*** podemos crear cabeceras de segundo nivel (subtítulos), esto relacionandolo con HTML, eso como crear un H2

~~~
Cabecera 2
----------
~~~

* Otra forma de crear cabeceras es usando ***#***, dependiendo de la cantidad de numerales que se use las cabeceras seran más pequeñas (de un nivel inferior)
~~~
#Cabecera 1
##Cabecera 2
###Cabecera 3
####Cabecera 4
#####Cabecera 5
~~~
Cabe mencionar que usar ***===*** para títulos y ***---*** para subtítulos es igual a usar ***#*** y ***##***, respectivamente.

# Sintaxis Básica en Markdown en tu blog

Un ejemplo muy básico de un texto en Markdown
Markdown es un lenguaje de marcado  como lo es HTML, pero es mucho más sencillo de utilizar, y puede hacerte las cosas más fáciles al momento de escribir los contenidos para tu blog
,

# H1
## H2
*Texto en itálica* y **Texto en negrita**
Lista ordenada
1. Primer elemento de la lista.
2. Segundo elemento.
3. Tercer Elemento.
Lista no ordenada
* Primer elemento
* Segundo elemento
Su salida en HTML
HyperText Markup Language es el lenguaje (código) que sirve para dar forma y entregar información adicional a las páginas web, como el titulo, la descripción o lo que va en negrilla o itálica.
, algo un poco más difícil de leer para una persona,

<h1>H1</h1>
<h2>H2</h2>
<p><em>Texto en itálica</em> y <strong>Texto en negrita</strong>
<p>Lista ordenada</p>
<ol>
   <li>Primer elemento de la lista.</li>
   <li>Segundo elemento.</li>
   <li>Tercer Elemento.</li>
</ol>
<p>Lista no ordenada</p>
<ul>
   <li>Primer elemento</li>
   <li>Segundo elemento</li>
</ul>
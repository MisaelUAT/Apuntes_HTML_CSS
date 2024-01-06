# Introduccion a HTML



Tienes que saber primero que html no es un lenguaje de programacion, es un lenguaje de marcado, es decir, que no tiene logica, solo es una forma de darle formato a un texto. En este caso lo que queremos es darle un formato a una pagina web y darle un esqueleto. Para eso en este curso veremos cosas basicas de HTML. Este lenguaje utiliza etiquetas para agregar elementos a la pagina como: Tablas,Listas,Imagenes,Audio,Video,etc.

## ¿Como funcionan las Etiquetas?
Estas etiquetas se componen de dos partes, la etiqueta de apertura y la etiqueta de cierre. La etiqueta de apertura es la que abre el elemento y la etiqueta de cierre es la que cierra el elemento. Por ejemplo:

```html
<Inicio>Esto es un parrafo</Final>
``` 
> Recuerda que algunas etiquetas se cerraran con el **/** al final de la etiqueta de apertura pero hay otras que no las necesitan.

**Consejo:** Siempre que trabajes con una o mas etiquetas, siempre la primera sera la ultima en cerrarse. 

Por ejemplo:
    
```html
<Etiqueta1>
    <Etiqueta2>
        <Etiqueta3>

        </Etiqueta3>
    </Etiqueta2>
</Etiqueta1>
```
> Como vez en este ejemplo la etiqueta 1 es la primera en abrirse y la ultima en cerrarse, mientras que las demas conforme se vayan abriendo se iran cerrando en orden.

- Ahora que hemos visto como funciona lo basico de las etiquetas, llego el momento de explicarte algunas que son fundamentales para el desarrollo de una pagina web.


## Etiquetas Basicas Predefinidas

| Etiqueta | Descripcion |
| --- | --- |
| `<html>` | Esta etiqueta es la que abre el documento HTML |
| `<head>` | Esta etiqueta es la que abre la cabecera del documento HTML |
| `<title>` | Esta etiqueta es la que abre el titulo del documento HTML |
| `<body>` | Esta etiqueta es la que abre el cuerpo del documento HTML |
| `<meta>` | Esta etiqueta es la que se encarga de especificar algunas configuraciones para que nos reconozca el navegador nuestra pagina |

## Estructura de Pagina Web

Antes de que hagamos maravillas en nuestro codigo, tenemos que saber como se estructura una pagina web, para eso tenemos que saber que una pagina web se compone de las siguientes partes:


| Etiqueta | Descripción |
| --- | --- |
| `<div>` | Define una sección en un documento. Se utiliza para agrupar elementos para aplicar estilos CSS o realizar tareas de manipulación con JavaScript. |
| `<span>` | Se utiliza para agrupar en línea elementos en un documento. |
| `<section>` | Define una sección en un documento. Se utiliza para agrupar contenido temáticamente relacionado. |
| `<article>` | Define contenido independiente que debería hacer sentido por sí mismo. |
| `<aside>` | Define contenido aparte del contenido al que está cerca en el documento. Se utiliza para contenido tangencialmente relacionado. |
| `<header>` | Define un contenedor para contenido introductorio o un conjunto de enlaces de navegación. |
| `<footer>` | Define un pie de página para un documento o sección. |
| `<nav>` | Define un contenedor para enlaces de navegación. |
| `<figure>` | Especifica contenido autónomo, como ilustraciones, diagramas, fotos, fragmentos de código, etc. |
| `<figcaption>` | Define una leyenda para un elemento `<figure>`. |
| `<main>` | Define el contenido principal o importante en el documento. Único por página y debe ser único. |
| `<p>` | Define un párrafo. |
| `<h1>` a `<h6>` | Define encabezados, `<h1>` es el encabezado de mayor rango y `<h6>` es el de menor rango. | |

> No te preocupes si no entiendes algunos significados de las etiquetas, ya que en el curso veremos como se utilizan y para que sirven.

![Estructura de una Pagina Web](https://www.snsmarketing.es/blog/wp-content/uploads/2017/04/banner_sns_dise%C3%B1o.jpg)

> Aqui solo se muestran algunas pero es solo para que te des una idea.

## Conclusiones
Ya que acabamos de ver algunas etiquetas, su funcionamiento, como funcionan y para que sirven. Es momento de ver y practicar en el siguiente capitulo los elementos de texto.
[Siguiente Capitulo](/HTML/Lection#2.md)
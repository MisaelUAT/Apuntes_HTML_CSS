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


| Etiqueta | Descripcion |
| --- | --- |
| `<html>` | Esta etiqueta es la que abre el documento HTML |
| `<head>` | Esta etiqueta es la que abre la cabecera del documento HTML |
| `<title>` | Esta etiqueta es la que abre el titulo del documento HTML |
| `<body>` | Esta etiqueta es la que abre el cuerpo del documento HTML |
| `<meta>` | Esta etiqueta es la que se encarga de especificar algunas configuraciones para que nos reconozca el navegador nuestra pagina |

<button onclick="">Oprime Aqui</button>



<script>

    function saludaUsuario(){
        alert("Hola Usuario");
    }

</script>
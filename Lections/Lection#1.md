# Principios Basicos de HTML

## Definicion
Es un lenguaje de marcado que se utiliza para el desarrollo de paginas de internet. Se trata de la sigla que corresponde a HyperText Markup Language, es decir, Lenguaje de Marcas de Hipertexto. 

## Funcion
Este nos va permitir armar estructuras de nuestra pagina web, como si fuera una casa en construccion. Esta va a ser la base de todo y la que va a depender el diseño y como se muestra con el usuario.

## Como funciona HTML
Para que nosotros podamos agregar contenido a nuestra pagina web, tenemos que usar **etiquetas y atributos**. Estas etiquetas son las que van a definir el contenido de nuestra pagina web.

### Etiquetas
Las etiquetas son aquellas palabras claves que nos ayudaran a poner diferentes tipos de contenido en nuestra pagina web. Normalmente siempre van a tener estas: <>, una etiqueta de apertura y una de cierre, pero hay algunas que no necesitan de una etiqueta de cierre. Ejemplo:
    
```html
<!--Etiqueta con Apertura y Cierre-->
<p> Hola Mundo </p>
<!--Etiqueta con Apertura-->
<br>
```
> **Recuerda:** que las etiquetas al momento de abrirlas se tienen que cerrar. Si no se cierran, el navegador no va a poder interpretar el codigo y no se va a mostrar el contenido.

### Atributos
Los atributos son aquellas palabras claves que nos ayudaran a darle caracteristicas a nuestras etiquetas. Estos siempre van a tener esta estructura: 

**nombre_atributo="valor"**. 

Ejemplo:

```html
<!--Aqui estamos agregando un titulo en un enlace llamado Hello World-->
<a title="Hello World"></a>
```

## Estructura Basica de HTML
Antes de continuar, tienes que saber que si quieres hacer un archivo de **html** tienes que usar una IDE (Integrated Development Environment) o un editor de texto.

> EL mas recomendado es Visual Studio Code, ya que es muy completo y tiene muchas extensiones que te pueden ayudar a la hora de programar.

Ahora si, vamos a ver la estructura basica de HTML:

![Estructura Basica de HTML](/assets/img/estructura_html.png)

*  **Etiqueta Doctype:** Esta etiqueta es la que nos va a permitir definir la version de HTML que vamos a usar. En este caso, vamos a usar la version 5.

*  **Etiqueta HTML:** Esta etiqueta es la que nos va a permitir definir el contenido de nuestra pagina web.

* **Etiqueta meta:** Se utiliza para proporcionar información sobre el documento HTML que no se muestra directamente en la página web, pero que es importante para los navegadores web y otros agentes de usuario que procesan el documento

*  **Etiqueta Head:** Es aquella en la que su funcion es contener informacion sobre el documento y que no sea visible para el usuario.

*  **Etiqueta Body:** Es aquella en la que su funcion es contener informacion que va a ser visible para el usuario.

### Notas
Si quieres saber un poco mas sobre este apartado dirijete a: [Consejos Iniciales de HTML](/Lections/Extra.md)
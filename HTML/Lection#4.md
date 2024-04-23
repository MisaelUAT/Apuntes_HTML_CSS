# Etiquetas de Estructura de una Pagina Web

Como vimos a principios del curso, las etiquetas de estructura son las que se utilizan para darle forma a una pagina web. Estas etiquetas son las que se utilizan para dividir la pagina en secciones y darle un orden a los elementos que se encuentran en ella. Cada una tiene una funcion y aqui veremos algunas de las mas importantes.

## Etiqueta Head

La etiqueta head es una etiqueta que se utiliza para indicarle al navegador informacion sobre la pagina web. Esta etiqueta no se muestra en la pagina web, pero es muy importante para el funcionamiento de la misma. Ya que puede incluir:

- Hojas de Estilo
- Scripts
- Metadatos
- Titulo de la Pagina

## Estructura

La estructura de la etiqueta head es la siguiente:

```html
<head>
    <!-- Titulo de la Pagina -->
    <title>Titulo de la Pagina</title>
    <!-- Hoja de Estilo -->
    <link rel="stylesheet" href="estilos.css">
    <!-- Script -->
    <script src="script.js"></script>
    <!-- Metadatos -->
    <meta charset="UTF-8">
</head>
```

### Ejemplo
Normalmente se mira asi cuando es una estructura basica:

![Head](/Assets/img/head.png)


## Etiqueta Body

La etiqueta body es una etiqueta que se utiliza para indicarle al navegador la estructura de la pagina web. Esta etiqueta es la que contiene todo el contenido de la pagina web, como texto, imagenes, videos, etc. En pocas palabras es todo lo visible en la pagina.

## Estructura

La estructura de la etiqueta body es la siguiente:

```html

<body>
    <!-- Contenido de la Pagina -->
    <h1>Titulo de la Pagina</h1>
    <p>Este es un parrafo de la pagina</p>
    <img src="imagen.jpg" alt="Imagen de la Pagina">
</body>
```
> El Body sera nuestro contenedor principal de la pagina web, en el se encontrara todo el contenido que se mostrara en la pagina.

### Ejemplo
Normalmente se mira asi cuando es una estructura basica:

![Body](/Assets/img/body.png)

> Como ven todo el contenido que se muestra en la pagina se encuentra dentro de la etiqueta body.


## Etiqueta Header

La etiqueta header es una etiqueta que se utiliza para indicarle al navegador la cabecera de la pagina web. Esta etiqueta es la que contiene el encabezado de la pagina web, como el logo, el menu de navegacion, etc.

## Estructura

La estructura de la etiqueta header es la siguiente:

```html
<header>
    <!-- Logo de la Pagina -->
    <img src="logo.jpg" alt="Logo de la Pagina">
    <!--Nombre de la Empresa-->
    <h1>Nombre de la Empresa</h1>
</header>
```

### Ejemplo

Normalmente se mira asi cuando es una estructura basica:

![Header](/Assets/img/header.png)

> Como ven el header es la cabecera de la pagina web, en el se encuentra el logo y el nombre de la empresa.

## Etiqueta Nav

La etiqueta nav es una etiqueta que se utiliza para indicarle al navegador la barra de navegacion de la pagina web. Esta etiqueta es la que contiene los enlaces de navegacion de la pagina web, como los enlaces a las diferentes secciones de la pagina.

## Estructura

La estructura de la etiqueta nav es la siguiente:

```html
<nav>
    <!-- Enlaces de Navegacion -->
    <a href="#">Inicio</a>
    <a href="#">Acerca de</a>
    <a href="#">Contacto</a>
</nav>
```

### Ejemplo

Normalmente se mira asi cuando es una estructura basica:

![Nav](/Assets/img/nav.png)

> Como ven el nav es la barra de navegacion de la pagina web, en el se encuentran los enlaces a las diferentes secciones de la pagina.


## Etiqueta Section

La etiqueta section es una etiqueta que se utiliza para indicarle al navegador una seccion de la pagina web. Esta etiqueta es la que contiene una seccion de la pagina web, como una seccion de noticias, una seccion de productos, etc. En pocas palabras son espacios que tienen relacion con nuestro contenido.

## Estructura

La estructura de la etiqueta section es la siguiente:

```html
<section>
    <!-- Contenido de la Seccion -->
    <h2>Titulo de la Seccion</h2>
    <p>Este es un parrafo de la seccion</p>
    <img src="imagen.jpg" alt="Imagen de la Seccion">
</section>
```

### Ejemplo

Normalmente se mira asi cuando es una estructura basica:

![Section](/Assets/img/section.png)

> Como ven el section es una seccion de la pagina web, en el se encuentra el contenido relacionado con el tema principal.


## Etiqueta Div

La etiqueta div es una etiqueta que se utiliza para indicarle al navegador un contenedor de la pagina web. Esta etiqueta es la que contiene un contenedor de la pagina web, como un contenedor de noticias, un contenedor de productos, etc. En pocas palabras son espacios que no tienen relacion con nuestro contenido.

## Estructura

La estructura de la etiqueta div es la siguiente:

```html
<div>
    <!-- Contenido del Contenedor -->
    <h2>Titulo del Contenedor</h2>
    <p>Este es un parrafo del contenedor</p>
    <img src="imagen.jpg" alt="Imagen del Contenedor">
</div>
```

### Ejemplo

Normalmente se mira asi cuando es una estructura basica:

![Div](/Assets/img/div.png)

> Como ven el div es un contenedor de la pagina web, en el se encuentra el contenido que no esta relacionado con el tema principal.


### Diferencias entre Section Y Div

| Característica | `<div>` | `<section>` |
| --- | --- | --- |
| Uso | Se utiliza para agrupar elementos sin ningún significado semántico. | Se utiliza para agrupar contenido relacionado y debe tener un encabezado. |
| Semántica | No tiene valor semántico. | Tiene valor semántico, indica una sección de un documento. |
| Encabezado | No requiere un encabezado. | Debería tener un encabezado. |
| SEO | No tiene impacto directo en SEO. | Puede mejorar el SEO al ayudar a los motores de búsqueda a entender la estructura del contenido. |


## Etiqueta Footer

La etiqueta footer es una etiqueta que se utiliza para indicarle al navegador el pie de la pagina web. Esta etiqueta es la que contiene el pie de la pagina web, como los derechos de autor, los enlaces a las redes sociales, etc.

## Estructura

La estructura de la etiqueta footer es la siguiente:

```html
<footer>
    <!-- Derechos de Autor -->
    <p>© 2021 Derechos de Autor</p>
    <!-- Redes Sociales -->
    <a href="#">Facebook</a>
    <a href="#">Twitter</a>
    <a href="#">Instagram</a>
</footer>
```

### Ejemplo

Normalmente se mira asi cuando es una estructura basica:

![Footer](/Assets/img/footer.png)

> Como ven el footer es el pie de la pagina web, en el se encuentra los derechos de autor y los enlaces a las redes sociales.

## Conclusión

Como vimos las etiquetas de estructura son muy importantes para darle forma a una pagina web. Cada una tiene una funcion y es importante saber como utilizarlas para que nuestra pagina web tenga una buena estructura y sea facil de leer.

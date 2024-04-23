# Etiquetas de Contenido Multimedia

Estas te ayudaran a insertar contenido multimedia en tu pagina web, como imagenes, videos, audio, etc, En pocas palabras son una estructura para poner contenido multimedia en tu pagina web.

## Etiqueta de Imagen

La etiqueta de imagen es una etiqueta que se utiliza para insertar imagenes en tu pagina web.

### Estructura

```html
<img src="URL de la imagen" alt="Descripcion de la imagen" width="numero de pixeles de ancho" height="numero de pixeles por alto">
```
Su estructura consiste en: 
- **src:** Es el atributo que se utiliza para indicar la URL de la imagen que se va a insertar.
- **alt:** Es el atributo que se utiliza para dar una descripcion de la imagen que se va a insertar.
- **width:** Es el atributo que se utiliza para indicar el ancho de la imagen(Es opcional ya que puedes manejarlo en css)
- **height:** Es el atributo que se utiliza para indicar el alto de la imagen(Es opcional ya que puedes manejarlo en css)


### Ejemplo

```html
<img src="/Assets/img/HTML5.png" alt="Logo de HTML5" width="50" height="50">
```

**Como se ve:**

<img src="/Assets/img/HTML5.png" alt="Logo de HTML5" width="50" height="50">


## Etiqueta de Video

La etiqueta de video es una etiqueta que se utiliza para insertar videos en tu pagina web.

### Estructura

```html
<video poster="URL de la imagen" controls autoplay loop>
  <source src="URL del video" type="tipo de video">
</video>
```

Su estructura consiste en:
- **poster:** Es el atributo que se utiliza para indicar la URL de la imagen que se va a mostrar antes de que el video se reproduzca.
- **controls:** Es el atributo que se utiliza para mostrar los controles del video. No se necesita especificar un valor.
- **autoplay:** Es el atributo que se utiliza para que el video se reproduzca automaticamente. No se necesita especificar un valor.
- **loop:** Es el atributo que se utiliza para que el video se reproduzca en bucle. No se necesita especificar un valor.

> **Nota:** La etiqueta source se utiliza para indicar la URL del video y el tipo de video que se va a reproducir.

### Ejemplo

```html
<video poster="/Assets/img/HTML5.png" controls autoplay loop>
  <source src="/Assets/video/HTML5.mp4" type="video/mp4">
</video>
```

Como se ve:

<video poster="/Assets/img/HTML5.png" controls autoplay loop>
  <source src="/Assets/videos/HTML_course.mp4" type="video/mp4">
</video>
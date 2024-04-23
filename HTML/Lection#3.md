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

> **Nota:** La etiqueta source se utiliza para indicar la ubicacion del video y el tipo de video que se va a reproducir.

### Ejemplo

```html
<video poster="/Assets/img/HTML5.png" controls autoplay loop>
  <source src="/Assets/video/HTML5.mp4" type="video/mp4">
</video>
```

Como se ve:

![Video HTML5](/Assets/img/videohtml.png)

## Etiqueta de Audio

La etiqueta de audio es una etiqueta que se utiliza para insertar audio en tu pagina web. Puedes usarla cuando quieras poner musica de fondo en tu pagina web.

### Estructura

```html
<audio controls autoplay loop>
  <source src="URL del audio" type="tipo de audio">
</audio>
```

Su estructura consiste en:
- **controls:** Es el atributo que se utiliza para mostrar los controles del audio. No se necesita especificar un valor.

- **autoplay:** Es el atributo que se utiliza para que el audio se reproduzca automaticamente. No se necesita especificar un valor.

- **loop:** Es el atributo que se utiliza para que el audio se reproduzca en bucle. No se necesita especificar un valor.

> **Nota:** La etiqueta source se utiliza para indicar la ubicacion del audio y el tipo de audio que se va a reproducir.

### Ejemplo

```html
<audio controls>
  <source src="/Assets/audio/Subwoofer Lullaby.mp3" type="audio/mp3">
</audio>
```

Como se ve:

![Audio](/Assets/audio/audioHTML.png)


## Etiqueta de Iframe

La etiqueta de iframe es una etiqueta que se utiliza para insertar contenido de otra pagina web en tu pagina web. En picas palabras seria una ventana que te muestra otra pagina web.

### Estructura

```html
<iframe src="URL de la pagina web" width="ancho de la ventana" height="alto de la ventana"></iframe>
```

Su estructura consiste en:
- **src:** Es el atributo que se utiliza para indicar la URL de la pagina web que se va a mostrar.
- **width:** Es el atributo que se utiliza para indicar el ancho de la ventana(Es opcional ya que puedes manejarlo en css)
- **height:** Es el atributo que se utiliza para indicar el alto de la ventana(Es opcional ya que puedes manejarlo en css)


### Ejemplo

```html
<iframe 
width="560" 
height="315" 
src="https://www.youtube.com/embed/S93nYy-Bxzo" frameborder="0" 
allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
</iframe>
```
#### Propiedades Extras:
- **frameborder:** Es el atributo que se utiliza para indicar si se muestra o no el borde de la ventana. Si se pone 0 no se mostrara el borde. Por defecto es 1.

- **allow:** Es el atributo que se utiliza para indicar que se puede hacer en la ventana. En este caso se puede acelerar, reproducir, escribir en el portapapeles, encriptar, usar el giroscopio y ver la imagen en la ventana.

- **allowfullscreen:** Es el atributo que se utiliza para indicar que se puede ver la ventana en pantalla completa.

Como se ve:

![Iframe](/Assets/img/iframeHTML.png)
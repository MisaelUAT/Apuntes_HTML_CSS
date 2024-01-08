# Introduccion a CSS
## ¿Que es CSS?
CSS es un lenguaje que se utiliza para darle estilo a las paginas web, es decir, para darle color, tamaño, forma, etc. a los elementos de la pagina web. Es fundamental ya que sin el, nuestra pagina solo seria texto plano y no tendria ningun atractivo visual.

## ¿Como se utiliza?
Existen muchas formas de usar css en html en las cuales estan:
- Etiqueta Style
- Etiqueta Link
- Atributo Style

### Forma 1: Etiqueta Style
Esta forma es la mas sencilla de usar, ya que solo se necesita una etiqueta de html y dentro de ella se escribe el codigo css.

#### Ejemplo
```html
<style>
    Etiqueta{
        Propiedad: Valor;
    }
<style>
```

### Forma 2: Etiqueta Link
Esta forma es la mas utilizada, ya que se puede crear un archivo css aparte y solo se necesita una etiqueta de html para enlazarlo.

#### Ejemplo
```html
<link rel="stylesheet" href="rutaArchivo">
```

### Forma 3: Atributo Style
Esta forma es la menos utilizada, ya que se necesita una etiqueta de html y dentro de ella se escribe el codigo css.

#### Ejemplo
```html
<Etiqueta style="Propiedad: Valor;">
```

## ¿Como se Manejan?
Se utiliza los que son atributos y selectores.

- **Los Selectores** son los que se utilizan para seleccionar un elemento de html y darle estilo. Existen diferentes tipos para seleccionar un elemento html, veremos en el siguiente capitulo.

### Ejemplo
```css
Etiqueta{
    
}
```
> Los selectores siempre tendran que abrisr y cerrar llaves.

- **Los Atributos** son los que se utilizan para darle estilo a un elemento de html. Existen diferentes tipos de atributos, veremos en el siguiente capitulo.

### Ejemplo
```css
Etiqueta{
    Propiedad: Valor;
}
```
> Los atributos siempre tendran que ir dentro de las llaves de los selectores y se les tiene que especificar un valor. AL mimo tiempo cerrar con un **;**.


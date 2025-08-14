
````markdown
# Introducción a las Etiquetas HTML

HTML (HyperText Markup Language) es el lenguaje de marcado estándar para crear páginas web. Las etiquetas son los componentes fundamentales de HTML, ya que definen la estructura de un documento y especifican el tipo de contenido que se está mostrando. Las etiquetas HTML se utilizan para estructurar texto, enlaces, imágenes, tablas y otros elementos dentro de una página web.

## Estructura Básica de una Etiqueta

Una etiqueta HTML suele tener la siguiente estructura:

```html
<etiqueta>Contenido</etiqueta>
````

* **<etiqueta>**: Es la etiqueta de apertura. Indica el comienzo de un elemento HTML.
* **Contenido**: Es el texto o los elementos que están dentro de la etiqueta.
* **</etiqueta>**: Es la etiqueta de cierre. Indica el final del elemento.

## Tipos Comunes de Etiquetas HTML

### 1. Etiquetas de Estructura

* `<html>`: Define el inicio de un documento HTML.
* `<head>`: Contiene metadatos como el título de la página, enlaces a hojas de estilo y scripts.
* `<title>`: Define el título que se muestra en la barra de título del navegador.
* `<body>`: Contiene el contenido visible de la página web.

### 2. Etiquetas de Texto

* `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`: Etiquetas de encabezado que indican la importancia del texto. `<h1>` es el más importante y generalmente se usa para el título principal de la página.
* `<p>`: Define un párrafo de texto.
* `<br>`: Inserta un salto de línea.
* `<strong>`: Define texto que debe mostrarse en negrita, indicando énfasis.
* `<em>`: Define texto en cursiva, utilizado para enfatizar una palabra o frase.

### 3. Etiquetas de Enlaces e Imágenes

* `<a href="URL">`: Crea un enlace a otra página o recurso.

  ```html
  <a href="https://www.ejemplo.com">Visitar Ejemplo</a>
  ```
* `<img src="URL" alt="descripción">`: Inserta una imagen. Asegúrate de proporcionar el atributo `alt` para describir la imagen.

  ```html
  <img src="logo.png" alt="Logo del sitio">
  ```

### 4. Etiquetas de Listas

* `<ul>`: Crea una lista no ordenada (con viñetas).
* `<ol>`: Crea una lista ordenada (con números).
* `<li>`: Define un elemento dentro de una lista.

Ejemplo:

```html
<ul>
  <li>Elemento 1</li>
  <li>Elemento 2</li>
  <li>Elemento 3</li>
</ul>
```

### 5. Etiquetas de Tablas

* `<table>`: Define una tabla.
* `<tr>`: Define una fila dentro de la tabla.
* `<td>`: Define una celda dentro de una fila.
* `<th>`: Define una celda de encabezado dentro de una tabla.

Ejemplo:

```html
<table>
  <tr>
    <th>Encabezado 1</th>
    <th>Encabezado 2</th>
  </tr>
  <tr>
    <td>Celda 1</td>
    <td>Celda 2</td>
  </tr>
</table>
```

### 6. Etiquetas de Formulario

* `<form>`: Define un formulario.
* `<input>`: Crea un campo de entrada para texto, contraseñas, etc.
* `<button>`: Crea un botón que se puede hacer clic.

Ejemplo:

```html
<form>
  <input type="text" placeholder="Escribe algo">
  <button type="submit">Enviar</button>
</form>
```

## Etiquetas Auto-Cerradas

Algunas etiquetas no requieren una etiqueta de cierre. Estas etiquetas se auto-cerran con una barra (`/`) dentro de la etiqueta de apertura. Ejemplos comunes son:

* `<img>`: Para insertar imágenes.
* `<br>`: Para saltos de línea.
* `<hr>`: Para insertar una línea horizontal.

Ejemplo:

```html
<img src="imagen.jpg" alt="Descripción">
<br>
<hr>
```

## Conclusión

Las etiquetas HTML son fundamentales para la construcción de una página web. Cada una tiene un propósito específico y contribuye a organizar y mostrar el contenido de manera adecuada. Conocer y entender cómo funcionan las etiquetas te permitirá crear sitios web más estructurados y accesibles.

```

Este es un archivo de ejemplo básico que cubre las etiquetas más comunes. Si necesitas más detalles o ejemplos de etiquetas más avanzadas, ¡avísame!
```

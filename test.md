# Ayudantía 3 - HTML + CSS

Lenguyaje de marcado basado en etiquetas

Hay etiquetas que necesitan contenido y otras que no. (Las que si, necesitan etiqueta de cerrado, las que no, no).

Visual Studio Code

# Etiquetas básica

---

Definición archivo HTML

```html
<!doctype html>           <!-- Tipo de documento -->
<html>                                    
	<head>                  <!-- Cabecera -->
		<meta charset="utf-8" />    <!-- Codificación del texto -->
		<title>Mi Primer Sitio :)</title>   <!-- Título del documento -->
	</head>

	<body>
                            <!-- Cuerpo -->
	</body>
<html>
```

# Etiquetas estructurales:

---

`<header>` Encabezado de la web, va el logo, paginas, menu, etc,

`<section>` secciones dentro de la página

`<article>` contenedor cerrado que guarda su propia info

`<aside>` barra lateral secundaria

`<footer>` pie de la página

`<div>` Contenedor general, contiene contenido, imagenes, texto, etc.

# Textos

---

Para definir títulos hay headings del 1 al 6: `<h1> <h2> ... <h6>`

Para los párrafos está la etiqueta `<p> texto.</p>`

Negrita: `<strong></strong>`. Itálicas: `<em></em>`

Bloque de Cita: `<blockquote></blockquote>`... Autor de la cita: `<cite>Javier</cite>`

Separador de ancho completo: `<hr/>`

# Enlaces

---

`<p>Hola, visita <a href="https://google.com/" title="Link de Google">el buscador</a>.</p>`Es necesario que el url en href tenga el protocolo completo (http(s))

el bloque <a> puede abrir el link en una página externa usando el atributo `target="_blank"`

# Imágenes

---

Se puede enlazar contenido dentro de la misma página o sitio, como también enlaces externos.

`<img src="imagen.jpg" alt="Imagen logo"/>` 

Se puede poner dentro de un div: ejemplo....

```html
<div>
	<img src="imagen.jpg" alt="Imagen logo"/>
</div>
<!-- Existen los atributos: -->
<img src="imagen.jpg" alt="Imagen logo" height="300" width="500"/> 
```

# Navegación:

---

Contiene la lista de elementos del menú de navegaciuón

Los elementos se deben presentar como una lista

```html
<nav>
	<ul>
		<li><a href="index.html" title="Inicio">Inicio</a></li>
		<li><a href="contacto.html" title="Contacto">Contacto</a></li>
	</ul>
</nav>
```

La lista con <ul> es una lista NO numerada (onda lista con puntitos)

```html
<nav>
	<ol>
		<li><a href="index.html" title="Inicio">Inicio</a></li>
		<li><a href="contacto.html" title="Contacto">Contacto</a></li>
	</ol>
</nav>
```

La lista con <ol> es una lista SI numerada (cada linea tiene una numeración)
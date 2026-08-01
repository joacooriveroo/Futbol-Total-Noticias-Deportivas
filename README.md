# Fútbol Total - Sitio Web de Noticias Deportivas

Sitio web informativo dedicado al fútbol nacional e internacional. El proyecto presenta noticias, resultados, calendarios, fixtures y contenido relacionado con diferentes competiciones deportivas.

Esta entrega incorpora una hoja de estilos CSS externa, una identidad visual compartida entre todas las páginas, la fuente Montserrat de Google Fonts y un pequeño código JavaScript para actualizar automáticamente el año del pie de página.

## Estructura del proyecto

* `index.html`: página principal del sitio, ubicada en la raíz.

* `pages/`: carpeta que almacena las páginas HTML secundarias:

  * `sobre-mi.html`
  * `proyectos.html`
  * `resultados.html`
  * `contacto.html`

* `styles/`: carpeta que contiene la hoja de estilos:

  * `styles.css`

* `assets/`: carpeta que contiene las imágenes y los recursos multimedia del sitio.

* `notas.txt`: archivo con información adicional sobre el desarrollo y las decisiones del proyecto.

* `README.md`: documentación general del sitio.

## Páginas

### Inicio

Contiene la presentación de Fútbol Total, noticias destacadas, últimas noticias y el fixture del Torneo Intermedio correspondiente a las series A y B.

### Sobre mí

Presenta el objetivo del sitio, la pasión por el periodismo deportivo y el contenido que los visitantes pueden encontrar en Fútbol Total.

### Proyectos

Muestra proyectos y coberturas relacionadas con el fútbol, sus clubes y diferentes competiciones.

### Resultados

Presenta información sobre la Copa Sudamericana 2026:

* Resultados de los partidos de ida.
* Resultados de los partidos de vuelta.
* Resultados globales.
* Próximos partidos.
* Equipos clasificados.
* Cruces de octavos de final.
* Próximas fases.
* Fuente de información.

### Contacto

Incluye información para comunicarse con Fútbol Total y enlaces relacionados con el proyecto.

## Tecnologías utilizadas

* HTML5
* CSS3
* JavaScript
* Google Fonts

## Características

* Uso de etiquetas semánticas de HTML5 como `header`, `nav`, `main`, `section`, `article`, `figure` y `footer`.
* Navegación interconectada mediante rutas relativas.
* Cinco páginas HTML vinculadas a una misma hoja de estilos.
* Imágenes con atributos `alt` descriptivos.
* Uso de `figure` y `figcaption` para las imágenes.
* Jerarquía de encabezados con `h1`, `h2` y `h3`.
* Enlaces externos abiertos en una pestaña nueva.
* Uso de `rel="noopener"` en enlaces externos.
* Año del pie de página actualizado automáticamente mediante JavaScript.
* Código HTML revisado mediante un validador.
* CSS organizado mediante comentarios.

## Diseño visual

El sitio utiliza la fuente Montserrat importada desde Google Fonts, con `sans-serif` como alternativa.

La paleta principal está formada por:

* Verde principal: `#123524`
* Verde secundario: `#1d593c`
* Verde del fixture: `#003c1b`
* Naranja de acento: `#ff8a1f`
* Naranja secundario: `#d95f02`
* Fondo claro: `#f2f5f3`
* Fondo alternativo: `#e4ebe7`
* Texto oscuro: `#202820`
* Pie de página: `#0b2117`

Se utilizaron diferentes tamaños y valores de `font-weight` para distinguir títulos, subtítulos y textos generales.

## Organización del CSS

El archivo `styles.css` contiene secciones separadas mediante comentarios:

* Estilos generales.
* Encabezado.
* Sección principal.
* Secciones de contenido.
* Noticias destacadas.
* Últimas noticias.
* Fixture del Torneo Intermedio.
* Imágenes.
* Resultados internacionales.
* Próximos partidos.
* Equipos clasificados.
* Cruces.
* Próximas fases.
* Fuente de información.
* Pie de página.

Los estilos se aplican mediante clases y no se utiliza `!important`.

Los identificadores se reservan para JavaScript.

## Fixture del Torneo Intermedio

El proyecto incluye imágenes correspondientes a la Serie A y la Serie B del Torneo Intermedio.

Se trabajó en:

* El centrado de los títulos.
* La posición de los cuadros de partidos.
* La alineación de los escudos.
* La separación uniforme entre los diferentes elementos.
* El cambio de la barra superior al color `#003c1b`.

## Validación

El código HTML fue revisado con un validador.

Se corrigió una advertencia en `resultados.html` agregando un encabezado `h2` a la sección que contiene la imagen de la Copa Sudamericana.

También se verificó:

* El cierre de las etiquetas.
* La jerarquía de encabezados.
* El uso de encabezados dentro de las secciones.
* La presencia de textos alternativos en las imágenes.
* La vinculación de `styles.css` en las cinco páginas.

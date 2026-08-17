Fútbol Total - Sitio Web de Noticias Deportivas

Fútbol Total es un sitio web informativo dedicado al fútbol uruguayo e internacional. La página presenta noticias, resultados y coberturas de diferentes competiciones deportivas.

El proyecto fue realizado con HTML y CSS. También utiliza un pequeño código JavaScript para actualizar automáticamente el año del pie de página.

Estructura del proyecto

index.html: página principal del sitio.

pages/: contiene las páginas secundarias:

sobre-mi.html

proyectos.html

resultados.html

contacto.html

pages/noticias/: contiene las páginas individuales de las noticias.

styles/: contiene la hoja de estilos styles.css.

assets/: contiene las imágenes, el logo y otros recursos.

assets/logos/: contiene los iconos de las redes sociales.

notas.txt: resume los principales cambios realizados.

Páginas

Inicio

El inicio funciona como una portada de noticias deportivas. Incluye dos noticias principales y cuatro noticias secundarias. Cada tarjeta es interactiva y abre la página de la noticia correspondiente.

Sobre mí

Presenta el objetivo del sitio, la relación con el periodismo deportivo y el contenido que se puede encontrar en Fútbol Total.

Proyectos

Muestra diferentes áreas de cobertura, el seguimiento de competiciones, el proceso de trabajo y algunos proyectos futuros.

Resultados

Presenta información sobre la Copa Sudamericana 2026:

Resultados de ida y vuelta.

Próximos partidos.

Horarios y estadios.

Equipos clasificados.

Cruces de octavos de final.

Próximas fases.

Fuente de información.

Contacto

Incluye información para comunicarse con Fútbol Total y enviar noticias, propuestas o correcciones.

Tecnologías utilizadas

HTML5

CSS3

CSS Grid

Flexbox

Media queries

JavaScript

Google Fonts

Diseño responsive

El sitio fue desarrollado con un enfoque mobile-first.

Los estilos base corresponden a celular y muestran las secciones apiladas. Después se agregaron dos breakpoints:

min-width: 768px para tablet.

min-width: 1024px para escritorio.

index.html y proyectos.html son las dos páginas trabajadas de forma completa para mobile, tablet y desktop.

En el inicio, las noticias se organizan mediante CSS Grid y grid-template-areas. En celular se muestran en una columna, en tablet pasan a dos columnas y en escritorio las noticias secundarias se distribuyen en cuatro columnas.

La página Proyectos también utiliza Grid. En celular presenta una columna, en tablet dos y en escritorio tres.

Flexbox se utiliza en el encabezado, el menú, el footer, las listas y otros elementos. La propiedad gap controla la separación entre los componentes.

Características

Uso de etiquetas semánticas como header, nav, main, section, article, figure y footer.

Navegación mediante rutas relativas.

Imágenes responsive con textos alternativos.

Uso de figure y figcaption cuando corresponde.

Jerarquía de encabezados con h1, h2 y h3.

Página activa del menú indicada mediante aria-current="page".

Navegaciones identificadas mediante aria-label.

Enlaces externos con target="_blank" y rel="noopener noreferrer".

Año del footer actualizado automáticamente mediante JavaScript.

CSS externo compartido por todas las páginas.

Diseño visual

Se utiliza la tipografía Montserrat, importada desde Google Fonts, con sans-serif como alternativa.

La paleta actual está inspirada en la estética de un portal deportivo y utiliza:

Celeste principal: #4595ba

Celeste secundario: #3d85a7

Gris carbón: #333333

Gris oscuro: #262626

Blanco: #ffffff

Gris claro: #f5f5f5

Texto principal: #222222

Los colores principales están guardados como variables dentro de :root.

El sitio utiliza un logo horizontal con texto blanco y fondo transparente. Su ancho cambia según el dispositivo para aprovechar mejor el espacio del encabezado.

Organización del CSS

El archivo styles.css se divide mediante comentarios en las siguientes partes:

Estilos generales.

Encabezado y navegación.

Secciones generales.

Portada de noticias.

Grid del inicio.

Grid de Proyectos.

Resultados y otras páginas.

Páginas individuales de noticias.

Pie de página.

Breakpoint de tablet.

Breakpoint de escritorio.

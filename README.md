# Gimnasio Coder

Sitio web multi-página desarrollado como proyecto práctico para la materia de Desarrollo Web, aplicando técnicas de maquetado con HTML semántico y CSS.


## Tecnologías utilizadas

- HTML5 (etiquetas semánticas: section, article, figure, figcaption).
- CSS (Flexbox, herencia, especificidad).
- SCSS (Variables, Mixins, Partials, Map).
- Bootstrap (Carousel, Navbar).
- Animate (Logo de la pagina).
- Animaciones con transition.
- Google Fonts.


## Características

- Maquetado responsive utilizando Flexbox (justify-content, gap, align-items).
- Uso de etiquetas semánticas para mejor estructura y accesibilidad.
- Carousel de imágenes implementado con Bootstrap.
- Navbar implementado con bootstrap.
- Tipografías personalizadas mediante Google Fonts.
- Organizacion de estilos con SCSS mediante Partials en la carpeta `scss/`.



## Estructura de Estilos (SCSS)

El proyecto utiliza SCSS modularizado en la carpeta `scss/`:

- `sass/main.scss`: Archivo principal donde se importan todos los partials.
- `sass/utilities/_variables.scss`: Variables globales (paleta de colores, tipografías, mapas de tema).
- `sass/utilities/_mixins.scss`: Funciones globales.
- `sass/base/_base.scss`: Reseteo de estilos básicos.
- `sass/base/_tipografia.scss`: Fuentes de textos, titulos y links.
- `sass/components/_buttons.scss`: Estilos para botones y componentes interactivos.
- `sass/layout/_header.scss`: Estilos para la estructura general del encabezado.
- `sass/layout/_nav.scss`: Pseudo-elementos para la barra de navegación.
- `sass/layout/_main.scss`: Estilos para la estructura general del main.
- `sass/layout/_cards.scss`: Estilos para la estructura general de las cards.
- `sass/layout/_footer.scss`: Estilos para la estructura general del footer.


## Cómo verlo localmente

1. Cloná el repositorio:
```bash
   git clone https://github.com/juliansilva912/94785gimnasiocoder-JulianSilva
```
2. Abrí el archivo `index.html` en tu navegador.


## Compilación de Sass

Para trabajar con los estilos en desarrollo y compilar a CSS:

1. Instalar dependencias:
   ```bash
   npm install

2. Enlazar mains.scss a styles.css:
   ```bash
   sass --watch sass/main.scss:styles/styles.css

## Estado del proyecto

Proyecto práctico en desarrollo para la materia de Desarrollo Web.
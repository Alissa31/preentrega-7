# Codigo Café

Sitio web estático para una cafetería con páginas de inicio, galería, menú, cursos y conocenos. El proyecto combina HTML, CSS y SCSS para mantener una estructura modular y reutilizable.

## Descripción

Codigo Café es un proyecto enfocado en presentar la identidad de negocio, ofrecer información sobre sus productos, cursos de barista, y una experiencia visual cálida con diseño adaptable.

## Tecnologías utilizadas

- HTML5
- CSS3
- SCSS
- Bootstrap 5
- AOS (animaciones de scroll)

## Estructura del proyecto

```text
.
├── index.html
├── css/
│   └── style.css
├── img/
├── pages/
│   ├── conocenos.html
│   ├── cursos.html
│   ├── galeria.html
│   └── menu.html
├── scss/
│   ├── base/
│   ├── components/
│   ├── layout/
│   ├── utilities/
│   └── style.scss
├── package.json
└── README.md
```

## Link

Link del sitio publicado via Gitpage: https://alissa31.github.io/preentrega-7/

## Personalización

Se puede ajustar:

- colores y tipografías en `scss/utilities/_variables.scss`
- layout y secciones en `scss/layout/`
- componentes como tarjetas en `scss/components/`
- contenido y textos en los archivos HTML dentro de `pages/` y `index.html`

## Mejores prácticas incluidas

- Organización del CSS en partials SCSS
- Diseño responsive con media queries
- Animaciones sutiles con keyframes
- Mejoras de accesibilidad y SEO en las páginas HTML
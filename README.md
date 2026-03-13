# Portafolio y CV Quarto - Luis Alfredo López Gonzales

Este repositorio contiene el código fuente de mi portafolio profesional y Currículum Vitae, construido utilizando [Quarto](https://quarto.org/).

## Estructura

- `index.qmd`: Página principal del portafolio.
- `content/cv.qmd`: Estructura principal del Currículum Vitae.
- `content/secciones/`: Archivos Markdown modulares con el detalle de la experiencia, educación, etc.
- `content/cv.css`: Hoja de estilos personalizada.

## Renderización

Para construir el sitio localmente, asegúrate de tener Quarto instalado y ejecuta:

```bash
quarto render
```

Los archivos generados se ubicarán en la carpeta `_site/`.

# Documento Detallado de Diseño (DDD)

## Descripción de tu trabajo

Este trabajo consiste en la creación de un sitio web personal académico como parte de la asignatura **Fundamentos de Ingeniería Informática**. El objetivo es documentar y presentar el progreso académico y los conocimientos adquiridos durante el primer curso del Grado en Ingeniería Informática.

El sitio está desarrollado íntegramente en HTML y CSS, con una estructura organizada por carpetas que incluye:

- Una página principal (`index.html`) con navegación clara y descripción general.
- Páginas adicionales en la carpeta `public/` que abarcan información personal, académica, temática y de contacto.
- Una hoja de estilos compartida en la carpeta `css/`.
- Imágenes y recursos visuales organizados en la carpeta `images/`.
- Documentación auxiliar (`README.md`, `.gitignore`, `LICENSE`) en la raíz del proyecto.
- Publicación en GitHub Pages y control de versiones a través de commits separados por sección.

## Problemas durante el desarrollo

Estos errores me ayudaron a aprender conceptos clave de desarrollo web que no había interiorizado del todo, y me permitieron mejorar mi forma de estructurar y mantener el código.

- **Uso incorrecto de rutas relativas**: Al principio, enlazaba mal las páginas internas desde el `index.html` porque no entendía bien cómo funcionaban las rutas relativas. Por ejemplo, usaba `about.html` en lugar de `public/about.html`. Lo solucioné revisando la estructura del proyecto y asegurándome de que todos los enlaces apuntaran correctamente según su ubicación.

- **Confusión entre estilos inline, internos y externos**: Empecé escribiendo estilos directamente en las etiquetas HTML (inline), lo que desordenaba el código. Luego los pasé al `<style>` del `<head>`, pero me di cuenta de que la práctica correcta era usar un archivo CSS externo. Así que centralicé todos los estilos en `css/style.css` y los enlacé en cada HTML.

- **Problemas al trabajar con Git**: Cometí el error de hacer muchos cambios antes de guardar un solo commit. Me costó entender cómo hacer commits pequeños y significativos. Al final aprendí a realizar un commit cada vez que añadía o modificaba una sección del sitio (como se pedía en las indicaciones).

## Conclusiones

Este proyecto me ha permitido aplicar de forma práctica los conocimientos adquiridos en HTML, CSS y organización de un sitio web profesional. Además, ha fomentado habilidades clave como:

- Documentación y estructuración de información técnica.
- Organización de código y carpetas en un entorno de desarrollo como VSCode.
- Uso de Git y GitHub para control de versiones, colaboración y publicación.
- Valoración crítica del papel del ingeniero informático en la sociedad y reflexión sobre el desarrollo ético y responsable de la tecnología.

El sitio refleja tanto el contenido académico trabajado en la asignatura, como el compromiso personal que he tenido a la hora de hacer este sitio web.

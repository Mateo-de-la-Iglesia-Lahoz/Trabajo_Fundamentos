# Trabajo para Fundamentos de la Ingeniería Informática

Este repositorio contiene el código fuente de un sitio web personal académico desarrollado como trabajo individual para la asignatura **Fundamentos de la Ingeniería Informática**. El sitio web sirve para documentar y mostrar los conocimientos adquiridos en la materia, presentando información sobre el estudiante, su formación, el grado que cursa, una asignatura específica y un tema de actualidad en informática.

## Estructura del Proyecto

La estructura de archivos y directorios es la siguiente:

- **index.html** – Página principal que introduce el sitio web.
- **/public/** – Carpeta que contiene las demás páginas HTML del sitio:
  - **about.html** – Sección "Sobre mí" con biografía y CV resumido.
  - **degree.html** – Sección "Grado" con información general sobre el Grado en Ingeniería Informática.
  - **fii.html** – Sección dedicada a la asignatura Fundamentos de la Ingeniería Informática (objetivos, contenidos, resultados de aprendizaje).
  - **topic.html** – Sección "Tema" con un artículo sobre el chip cuántico *Majorana 1* de Microsoft.
  - **net.html** – Sección "Red de compañeros" (enlaces a sitios de compañeros, inicialmente en construcción).
  - **contact.html** – Sección "Contacto" con un formulario de contacto (no funcional, solo HTML).
- **/css/** – Carpeta de estilos:
  - **style.css** – Hoja de estilo común utilizada por todas las páginas.
- **/images/** – Carpeta donde se almacenan las imágenes utilizadas en el sitio (fotos de perfil, ilustraciones, etc.).
- **README.md** – Este documento de descripción y guía del proyecto.
- **LICENSE** – Licencia de uso (MIT License) para el contenido de este repositorio.
- **.gitignore** – Archivo de configuración para ignorar archivos innecesarios en el control de versiones.

## Cómo ver el sitio

Para visualizar el sitio web, abre el archivo `index.html` en un navegador web. Desde la página de inicio podrás navegar a todas las secciones mediante el menú de navegación.

Si has clonado este repositorio, simplemente abre `index.html` con tu navegador (por ejemplo, haciendo doble clic sobre el archivo o usando la opción "Open with Live Server" en Visual Studio Code).

Además, este sitio está preparado para publicarse usando **GitHub Pages**. Si se configura el repositorio para Pages, la página debería estar disponible en una URL pública (por ejemplo, `https://<usuario>.github.io/<repositorio>/`). En ese caso, la navegación entre páginas funcionará correctamente mediante los enlaces relativos ya configurados.

## Uso y Personalización

Puedes utilizar y modificar libremente el código de este sitio para adaptarlo a tus necesidades académicas o personales. Algunas recomendaciones para personalizarlo:

- Reemplaza las imágenes de ejemplo en la carpeta **/images** por tus propias fotografías (asegúrate de actualizar las rutas `src` en el HTML si cambias los nombres).
- Edita el contenido de las secciones HTML para reflejar tu información personal, detalles de tu grado o el tema que quieras presentar. El texto incluido sirve como guía o ejemplo.
- Verifica que todos los enlaces de la sección "Red de compañeros" (cuando los agregues) funcionen correctamente.
- Si deseas agregar más estilo, puedes ampliar el archivo CSS o incluso incluir otras fuentes o colores, manteniendo una estética clara y profesional.

## Detalles de Implementación

- **HTML5 y CSS3:** Todas las páginas siguen estándares HTML5 (estructura semántica con `<header>`, `<nav>`, `<main>`, `<footer>`, etc.) y usan CSS externo para el estilo. El código ha sido validado para asegurar su corrección.
- **Diseño responsivo:** Se ha incluido la meta etiqueta de viewport y reglas CSS flexibles para que el sitio se visualice correctamente en dispositivos móviles y distintas resoluciones de pantalla.
- **Accesibilidad:** Se han proporcionado textos alternativos en las imágenes (`alt`), etiquetas en los formularios (`label`), y suficiente contraste de color (texto oscuro sobre fondo claro, y viceversa en la navegación) para mejorar la accesibilidad del sitio.
- **Navegación:** El menú de navegación aparece en todas las páginas, facilitando el acceso a cada sección. La página activa se resalta en el menú.
- **Formulario de contacto:** Incluye campos de texto, email y área de texto, usando tipos de input adecuados y atributos HTML5 (`required`, `placeholder`). No hay funcionalidad de envío (es una simulación), pero los campos pueden rellenarse y validarse localmente por el navegador.
- **Control de versiones:** Cada página del sitio se añadió en commits separados, manteniendo un historial claro de cambios. Para futuras colaboraciones o revisiones, se ha añadido como colaborador al usuario **hectormolgar** (el profesor de la asignatura).

## Licencia

Este proyecto se distribuye bajo la licencia MIT, lo que significa que puedes usar, modificar y distribuir el código libremente, siempre y cuando incluyas la nota de copyright y la renuncia de garantía. Consulta el archivo [LICENSE](LICENSE) para más detalles.

---
*Desarrollado por Mateo de la Iglesia Lahoz como proyecto de la asignatura Fundamentos de la Ingeniería Informática, 2025.*

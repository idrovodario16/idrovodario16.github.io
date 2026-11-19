# Darío Idrovo · Full Stack & Datos

Portafolio público: https://idrovodario16.github.io/

Sitio estático en español con proyectos destacados, demos, código, habilidades y contacto por LinkedIn. Los paneles de producto son vistas ilustrativas con datos ficticios y se identifican como tales.

## Publicación

En Settings → Pages, seleccionar **Deploy from a branch**, rama **main** y carpeta **/(root)**. GitHub Pages publica el contenido al actualizar esa rama. `.nojekyll` permite servir directamente los archivos estáticos. No requiere instalar paquetes ni contratar alojamiento.

## Edición

- `index.html`: contenido y enlaces.
- `style.css`: diseño responsive y movimiento reducido.
- `script.js`: año del pie de página.
- `assets/`: vistas ilustrativas y favicon SVG.

Validar `node --check script.js` y revisar el diseño en escritorio y móvil antes de publicar. El portafolio no usa formularios, analítica de visitantes ni dependencias externas de JavaScript.

La demo estática de cada proyecto y sus APIs se documentan por separado. Este sitio no cambia el funcionamiento, los datos ni los despliegues de NexusCore o NexusInsight.

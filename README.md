# Simulacro EB-A — Sesión I (GitHub Pages)

## Archivos
- `index.html`: sitio interactivo.
- `assets/simulacro-eb-a-sesion-I.pdf`: cuadernillo original.

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en GitHub.
2. Sube `index.html` y la carpeta `assets` completa (incluye el PDF).
3. Abre **Settings → Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`, y guarda.
6. Espera la publicación y comparte la URL que GitHub Pages te muestre.

## Funcionamiento y limitaciones
- La clave y las áreas se cargan desde la hoja Excel entregada, para las 120 preguntas de la Sesión I.
- Cada pregunta tiene 120 segundos; al agotarse el tiempo pasa automáticamente a la siguiente.
- Al finalizar, el navegador descarga un `.txt` con estudiante, grado, respuestas, clave, aciertos y resultados por área y total.
- **Importante:** GitHub Pages es alojamiento estático. La descarga queda en el dispositivo del estudiante; el docente no recibe los archivos automáticamente. Para centralizar resultados se requiere un backend o un formulario/servicio externo.
- La clave de respuestas se incluye en el JavaScript del sitio y un usuario con conocimientos básicos puede inspeccionarla. No se debe usar como evaluación de alta seguridad.
- El PDF tiene diagramas e imágenes que se consultan en el visor; el estudiante debe localizar allí el número de pregunta correspondiente.

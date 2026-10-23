# Logística · VI Semana de la Geofísica

Tablero público para consultar las actividades del 3 al 7 de noviembre de 2026.

- [Vista pública](https://Anagabrielamantilla.github.io/logistica-semana-geofisica/)
- [Panel privado de edición](https://logistica-semana-geofisica.girls-geologist.chatgpt.site/admin)

La página pública permite consultar, buscar y filtrar; no permite guardar cambios. El panel de administración verifica la cuenta de ChatGPT en el servidor y guarda los cambios en almacenamiento compartido. No se incluyen contraseñas ni tokens en este repositorio.

## Ajustes con Codex

Antes de cambiar actividades o responsables, descargar el estado actual desde `https://logistica-semana-geofisica.girls-geologist.chatgpt.site/api/board`. Actualizar `data.json` usando ese estado como base y asignar un valor nuevo y único a `revision`. Publicar el commit en `main`. El servicio aplica la nueva revisión al cargar el tablero; las ediciones del panel se mantienen entre cambios de código mientras `revision` no cambie. No usar una copia antigua de `data.json` como base porque podría reemplazar ajustes recientes del panel.

Los cambios visuales se realizan en `index.html` y los publica GitHub Pages. El panel y su servidor se mantienen en Sites desde el chat original de Codex. Los permisos del servidor no dependen de controles HTML.

El repositorio es público; únicamente su propietaria y las aplicaciones autorizadas por ella tienen permisos de escritura. No se han añadido colaboradores.

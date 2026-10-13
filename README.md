# Compendio de Combate V16 · GitHub Pages

Sube **todos los archivos** de esta carpeta a la raíz del repositorio: `index.html`, `sw.js`, `manifest.webmanifest`, los tres íconos y este README.

## Cambios V16
- Actualización de la PWA: se revisan versiones al abrir/volver a la app y periódicamente. Un aviso permite aplicar la versión nueva. No borra personajes, encuentros, PNJ, conjuros ni libros importados.
- Se elimina el bloque de edición “Enemigos y PNJ” de Combate; los monstruos se buscan en Bestiario. Los enemigos existentes se mantienen en iniciativa y daño rápido.
- Nueva pestaña PNJ: nombre, rol, lugar encontrado, historia, características, notas y relaciones; búsqueda y guardado local.
- Exportar partida también respalda los PNJ; importar partidas antiguas sigue funcionando.

**Importante:** los PNJ y encuentros se guardan en el almacenamiento local de ese navegador. Antes de borrar datos de Safari, exporta la partida. La biblioteca de libros/conjuros puede tener almacenamiento separado.

Para activar GitHub Pages: Settings → Pages → Deploy from a branch → main → /(root). Las actualizaciones pueden tardar unos minutos en publicarse. Si abres un archivo HTML local, no se activa la PWA: usa la dirección HTTPS del sitio publicado.

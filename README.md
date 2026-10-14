# DM.AID 1.0.0 · Dungeon Master Aid

**Run the game. Rule the story.**

Versión de marca sobre el Compendio de Combate V27. Conserva combate, personajes, bestiario, hechizos, PNJ, objetos y tiendas, y mantiene las mismas claves de almacenamiento para no migrar ni eliminar datos existentes.

## Publicar en GitHub Pages

1. Descomprime el ZIP.
2. Sube **todos los archivos de esta carpeta** a la raíz del repositorio, sustituyendo los anteriores (Add file → Upload files → Commit changes).
3. Si aún no lo configuraste, activa GitHub Pages en Settings → Pages → Deploy from a branch → main / root.
4. Abre la URL publicada y comprueba el nuevo título DM.AID. En iPad, quizás debas eliminar el acceso antiguo y añadir la nueva PWA a la pantalla de inicio para refrescar su nombre e icono.

**Importante:** exporta un respaldo de la partida antes de actualizar. El servicio offline usa una nueva versión de caché; los datos locales no se borran por el cambio de marca. No se incluyen libros comerciales de D&D; las fuentes se importan desde la aplicación.

## Archivos

- `index.html`: aplicación completa.
- `manifest.webmanifest`: identidad y metadatos de instalación.
- `sw.js`: PWA y actualización de caché.
- `icon-180.png`, `icon-192.png`, `icon-512.png`: nuevo d20 para Safari y PWA.
- `brand-art.jpg`: identidad visual DM.AID.
- `README.md`: estas instrucciones.

La ilustración original del logo se ha adaptado al icono. DM.AID es un proyecto personal no afiliado a Wizards of the Coast.

# Estudio de Doblaje · descargas (CLAUDE.md)

Repositorio **público** solo de *releases*: instaladores de Estudio de Doblaje y el motor de Whisper con Vulkan. **No tiene código fuente** y no debe tenerlo — es el destino de lo que compila `guion-timecodes-whisper-` (privado). Ver `README.md`.

## Reglas que no se negocian

- No se sube código aquí, solo `README.md`, imágenes para el README (`img/`) y lo que publican los *workflows* del otro repo (`release.yml`, `motor-whisper.yml`, con el *token* `DESCARGAS_TOKEN`).
- La app (`version.py` → `REPO_DESCARGAS`) busca aquí sus actualizaciones y el motor de Whisper con Vulkan. No cambies el nombre de este repositorio sin actualizar esa constante.
- Las etiquetas `v*` publican un *release* marcado como la versión estable o de prueba (según si llevan `-betaN`); las etiquetas `motor-whisper-*` publican el motor. Quien sube la etiqueta en `guion-timecodes-whisper-`, publica aquí.

## Cómo se integran los PR

Conserva los commits de quien contribuye tal cual (mensaje, autor, `Co-Authored-By`) al integrar — no los resumas ni los traduzcas. Sin `gh` disponible en este entorno: rebasa los commits originales sobre `main` en vez de un *squash* con mensaje propio; si hace falta *squash*, usa el *subject* y *body* originales y agrega las líneas `Co-Authored-By` originales junto a las que correspondan.

## Licencia

El núcleo de la app es GPL-3.0; el módulo Pro que trae el instalador oficial es cerrado y se rige por sus propios términos. Ver la sección de licencia en `README.md`.

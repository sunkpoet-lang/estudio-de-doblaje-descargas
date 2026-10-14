# TODO

Propuestas de mejora para el repositorio de descargas, a partir de una revisión del 13 de octubre de 2026 (CST). Son sugerencias: cada punto lo decide Daniel.

## Prioridad alta

- [ ] **Código fuente de lo que se publica aquí.** Los instaladores se presentan como GPL-3.0 en su núcleo, pero el código no está disponible. Resolverlo en el repositorio de la app (ver su `TODO.md`) y ajustar después la sección de licencia del README.

## Prioridad media

- [ ] **Checksums.** Adjuntar un `SHA256SUMS.txt` a cada *release* para poder verificar las descargas.
- [ ] **Mac y Linux en la 2.8.** Las versiones `v2.8.0-beta.N` solo traen el instalador de Windows. Agregar los de Mac y Linux cuando se compilen, o explicar en las notas que esa beta es solo para Windows.
- [ ] **Avisos de terceros.** Adjuntar o enlazar las licencias de FFmpeg, whisper.cpp, llama.cpp y los modelos que van en el instalador.

## Prioridad baja

- [ ] **Notas de *release* por plataforma**, con lo que cambia y los avisos de seguridad de cada sistema (instalador sin firmar, app sin notarizar).

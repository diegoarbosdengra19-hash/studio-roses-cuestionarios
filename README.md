# Studio Roses · Cuestionarios de la fase 1

Páginas estáticas de Taltalab para que Rafa y Cori respondan hablando o escribiendo.
- `rafa.html` y `cori.html`: 22 preguntas en 6 bloques, una por pantalla.
- `app.js`: graba la voz en la propia página (MediaRecorder) y la guarda en el navegador (IndexedDB). Si el navegador ofrece dictado, también escribe el texto en directo.
- Al final se envían los audios y el texto (compartir del móvil) o se descargan en un .zip (`jszip.min.js`, JSZip 3.10.1, MIT).
- No hay servidor ni base de datos: nada sale del dispositivo hasta que la persona lo envía.

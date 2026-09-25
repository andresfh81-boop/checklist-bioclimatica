# Checklist bioclimática (PWA offline)

Checklist de control de calidad para pérgolas bioclimáticas (UMARA / LLAZA · CTRL-CAL-PERGOLA-01).
La primera página es la portada (Orden, Cliente, Fecha, Revisado). Se puede rellenar a mano o
arrastrando el PDF del pedido/presupuesto, que se lee en el propio navegador (pdf.js, sin subir nada).

Funciona sin conexión una vez abierta la primera vez, y se puede instalar como app.

## Uso

Abre la URL de GitHub Pages en cualquier ordenador o móvil, rellena y **imprime (Ctrl+P)**
o guarda como PDF.

## Actualizar la app

Cada vez que cambies `index.html`, sube los cambios (`git add -A && git commit -m "..." && git push`)
y sube en 1 el número de `CACHE_NAME` en `sw.js` (p. ej. `checklist-v2`) para que los equipos
descarguen la versión nueva.

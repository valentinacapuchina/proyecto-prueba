# Operaciones por origen

Dashboard de una sola página (`index.html`) que muestra, para Argentina, Paraguay y Brasil:
operaciones, toneladas, proveedores, clientes y destinos.

## Datos

El código no contiene datos ni enlaces. Al abrir la página se piden dos enlaces y se guardan
solo en el `localStorage` del navegador:

- Hoja **ALL** de Control de embarque 2.0 (encabezados en la fila 2).
- Hoja **Database suppliers** (encabezados en la fila 1), de donde sale el origen por exportador.

Cada enlace puede ser una URL de la API de Sheets (`.../values/<hoja>?key=...`) o un CSV publicado.

## Uso

Abrí `index.html` en el navegador, o publicalo con GitHub Pages.
No subas claves de API ni enlaces al repositorio.

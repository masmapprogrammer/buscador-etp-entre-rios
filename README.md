# Buscador de educación técnica e industria — Entre Ríos

Sitio estático para GitHub Pages: buscador, filtros y mapa (Leaflet) centrado en la EET Nº 35 de Crespo.

## Publicación
1. Creá un repositorio y subí el contenido de esta carpeta a la rama `main`.
2. En Settings → Pages elegí "Deploy from a branch", rama `main`, carpeta `/ (root)`.
3. Abrí la URL que GitHub publica.

## Si el mapa muestra error 403
Abrir `index.html` como archivo local (`file://`) puede hacer que algunos proveedores de mapas rechacen las teselas. Usá GitHub Pages o un servidor local (`python -m http.server`).

## Datos
- `data/data.js`: usado por el sitio. `data/registros.json`: misma información.
- Relevamiento preliminar, no padrón oficial. Verificar domicilios, vigencia y convenios.

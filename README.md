# Red ETP · Entre Ríos

Sitio estático para GitHub Pages. Muestra escuelas técnicas/agrotécnicas e industrias del Parque Industrial de Crespo, con distancias geodésicas desde la EET N.º 35.

## Publicar

1. Reemplazá los archivos del repositorio por el contenido de esta carpeta.
2. Confirmá que `index.html` esté en la raíz y `assets/app.js` y `assets/data.js` dentro de `assets`.
3. En GitHub: **Settings → Pages → Deploy from a branch → main → /(root)**.
4. Esperá el despliegue y recargá con `Ctrl+F5`.

## Cartografía

El mapa usa OpenStreetMap y cambia automáticamente a Esri Calles si las teselas OSM fallan. Los botones de cada ficha abren el punto o calculan la ruta desde la EET 35 en Google Maps.

## Precisión

Las distancias mostradas en las fichas son en línea recta. La ruta vial y su distancia real se calculan al abrir Google Maps. Algunas alturas del Parque Industrial no están individualizadas en OpenStreetMap: en esos casos el dato se identifica como aproximado por calle o intersección.

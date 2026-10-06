# Shipham Parish Council Interactive Map

Public interactive mapping platform for Shipham Parish Council.

## Structure

- `index.html` - the public map interface.
- `layers/` - GeoJSON and other publishable map layers.

## Adding a GeoJSON layer

1. Export the GIS layer to GeoJSON using WGS 84 / EPSG:4326.
2. Place the file in `layers/`.
3. Add a corresponding entry to the map configuration in `index.html`.
4. Check the source licence, attribution and whether the data is suitable for public release.

The site is published through GitHub Pages.

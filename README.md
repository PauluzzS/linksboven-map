# LinksBoven Map

Brondata voor de LinksBoven-kaart: een GeoJSON met afdelings-/gemeentegrenzen en bijbehorende metadata
(zoals naam/slug en eventuele externe links).

## Inhoud

- `linksboven-afdelingen.geojson` — GeoJSON FeatureCollection met polygonen/multipolygonen per afdeling/gemeente.

## Gebruik

### In een webkaart (Leaflet / MapLibre / etc.)
Laad het GeoJSON als dataset en render de geometrie + properties in je kaartlaag / popups.

# LinksBoven Map

Brondata voor de LinksBoven-kaart: een GeoJSON met afdelings-/gemeentegrenzen en bijbehorende metadata
(zoals naam/slug en eventuele externe links). Gedeeld onder de Anti-Capitalist Software License.

## Waarom deze licentie?

Dit project wil **hergebruik mogelijk maken zonder dat het kan worden ingezet voor het onttrekken van waarde aan werkers**.
Kort gezegd: we delen dit graag met individuen, non-profits, onderwijs en democratische/coöperatieve organisaties,
maar niet voor toepassingen die primair draaien op winstmaximalisatie door arbeid structureel onder te belonen
(of door dwang/geweld via politie/militair).

De term “Software” in deze repository omvat ook de dataset (`linksboven-afdelingen.geojson`).
Zie `LICENSE.md` voor de volledige tekst.

### Twijfel of jouw gebruik past?

Open een issue met een korte beschrijving van je organisatie en use-case, dan kijken we mee.
Aanvullende toestemming voor non-extractieve doeleinden wordt per geval beoordeeld.

## Inhoud

- `linksboven-afdelingen.geojson` — GeoJSON FeatureCollection met polygonen/multipolygonen per afdeling/gemeente.
- `LICENSE.md` — Anti-Capitalist Software License (v1.4)

## Gebruik

### In een webkaart (Leaflet / MapLibre / etc.)

Laad het GeoJSON als dataset en render de geometrie + properties in je kaartlaag / popups.

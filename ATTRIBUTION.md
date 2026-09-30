# Attribution

TTimer track data (`catalog.json` and `tracks/*.json`) is made available under
the **Open Database License (ODbL) 1.0** -- see `LICENSE`
(https://opendatacommons.org/licenses/odbl/1-0/).

It is derived from:

- **OpenStreetMap** -- track centrelines, pit lanes and start/finish positions.
  © OpenStreetMap contributors, available under the ODbL 1.0.
  https://www.openstreetmap.org/copyright
- **Wikidata** -- venue names and coordinates, released under CC0 1.0.
  https://www.wikidata.org/

Gates were placed on OpenStreetMap geometry (or the rider's own recorded GPS
laps) and confirmed by eye; sector gates are generated (`sector_source:
"generated"`), not official circuit timing sectors. No gate was traced from
Google Maps imagery.

Each track file records its own `source`, `license` and `source_detail`
(OSM way ids and the gate confirmation date).

If you redistribute this database or a derivative of it, you must keep this
attribution, offer the result under the ODbL 1.0, and keep it open.

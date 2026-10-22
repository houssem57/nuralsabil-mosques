# Nur al Sabil – mosque tiles

Mosques (`amenity=place_of_worship` + `religion=muslim`) from OpenStreetMap, one JSON file per 1°×1° tile,
for the Nur al Sabil app. Rebuilt every month by a GitHub Action; every push replaces the whole repository,
so don't edit anything here.

- `tiles/<south>_<west>.json`, e.g. `tiles/53_9.json` = 53–54° N, 9–10° E. Each file also holds the mosques
  up to 10 km beyond the tile's edges. A tile without mosques has an empty list; a tile outside the covered
  regions has no file.
- `index.json`: date, covered regions, counts.

## Licence

Data © OpenStreetMap contributors, available under the
[Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/).
See https://www.openstreetmap.org/copyright. This collection is a derived database and is likewise
available under the ODbL.

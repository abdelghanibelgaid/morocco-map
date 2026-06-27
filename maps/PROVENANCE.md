# Data Provenance

This document records the provenance of map files included in this repository.

## Source geometry

The original Morocco geometry was manually authored by the maintainers of this repository. No third-party geometry was copied, imported, or derived to create the coordinate geometry. The resulting polygons were manually reviewed and normalized for Morocco’s current 12-region administrative structure.

## Administrative structure

The map data represents Morocco’s current 12 first-level administrative regions.

Region names and identifiers were normalized for compatibility:

- MA-01 through MA-12
- 12 first-level administrative regions
- WGS84 / EPSG:4326

## Included map files

| File | Format | Source | Status |
|---|---|---|---|
| `maps/morocco.geojson` | GeoJSON | Manually authored | available |
| `maps/morocco.topojson` | TopoJSON | Derived from `maps/morocco.geojson` | available |

## Derived formats

Additional formats may be added to this repository, such as GeoPackage, Shapefile, SVG, PMTiles, or MBTiles.

Unless otherwise stated, these files are derived from the original manually authored GeoJSON file: `maps/morocco.geojson`

Each new format should be added to the table below.

| File | Format | Derived from | Notes |
|---|---|---|---|
| `maps/morocco.gpkg` | GeoPackage | `maps/morocco.geojson` | planned |
| `maps/morocco.shp` | Shapefile | `maps/morocco.geojson` | planned |
| `maps/morocco.svg` | SVG | `maps/morocco.geojson` | planned |

## License

The dataset and derived files are released under the repository MIT License.

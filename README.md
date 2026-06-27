<div align="center">

# morocco-map

![software](https://img.shields.io/badge/software-26-blue)
![approved](https://img.shields.io/badge/approved-1-success)
![contributions](https://img.shields.io/badge/contributions-welcome-brightgreen)
![license](https://img.shields.io/badge/license-MIT-green)

Reference geographic data and compatibility tracking for Morocco maps across open-source ecosystems.

</div>

This repository provides Morocco map files and tracks open-source software where Morocco map support may need to be audited, documented, or updated. The goal is to make Morocco’s current 12-region administrative structure easier to use across BI dashboards, GIS portals, data-science tools, and open-source visualization libraries. Data provenance is documented in [`maps/PROVENANCE.md`](maps/PROVENANCE.md).

## Target software

| Tool / repository | Category | Status | Link |
|---|---|---|---|
| Apache Superset | BI / dashboard | `approved-merged` | [Merged PR](https://github.com/apache/superset/pull/41021) |
| Natural Earth Vector | Foundational geodata | `audit-needed` | [Repository](https://github.com/nvkelso/natural-earth-vector) |
| Highcharts Map Collection | Web charting / maps | `audit-needed` | [Repository](https://github.com/highcharts/map-collection-dist) |
| Plotly.js / Plotly.py / Dash | Web + Python visualization | `audit-needed` | [Plotly.js](https://github.com/plotly/plotly.js), [Plotly.py](https://github.com/plotly/plotly.py), [Dash](https://github.com/plotly/dash) |
| Vega Datasets / Vega-Lite / Altair | Visualization grammar ecosystem | `audit-needed` | [Vega Datasets](https://github.com/vega/vega-datasets), [Vega-Lite](https://github.com/vega/vega-lite), [Altair](https://github.com/vega/altair) |
| Elastic EMS File Service / Kibana | Search / government dashboards | `audit-needed` | [EMS File Service](https://github.com/elastic/ems-file-service), [Kibana](https://github.com/elastic/kibana) |
| Apache ECharts | Web charting | `docs-needed` | [Repository](https://github.com/apache/echarts) |
| Metabase | BI / dashboard | `docs-needed` | [Repository](https://github.com/metabase/metabase) |
| Grafana | Monitoring / observability | `docs-needed` | [Repository](https://github.com/grafana/grafana) |
| Leaflet | Web GIS renderer | `docs-needed` | [Repository](https://github.com/Leaflet/Leaflet) |
| OpenLayers | Web GIS renderer | `docs-needed` | [Repository](https://github.com/openlayers/openlayers) |
| MapLibre GL JS | Vector maps / web GIS | `docs-needed` | [Repository](https://github.com/maplibre/maplibre-gl-js) |
| deck.gl / kepler.gl | Geospatial analytics | `docs-needed` | [deck.gl](https://github.com/visgl/deck.gl), [kepler.gl](https://github.com/keplergl/kepler.gl) |
| GeoServer | Geospatial server | `format-needed` | [Repository](https://github.com/geoserver/geoserver) |
| QGIS | Desktop GIS | `format-needed` | [Repository](https://github.com/qgis/QGIS) |
| R sf | R geospatial | `docs-needed` | [Repository](https://github.com/r-spatial/sf) |
| R leaflet | R web maps | `docs-needed` | [Repository](https://github.com/rstudio/leaflet) |
| R tmap | R thematic maps | `docs-needed` | [Repository](https://github.com/r-tmap/tmap) |
| R rnaturalearth | R Natural Earth access | `audit-needed` | [Repository](https://github.com/ropensci/rnaturalearth) |
| GeoPandas | Python geospatial | `docs-needed` | [Repository](https://github.com/geopandas/geopandas) |
| Folium | Python web maps | `docs-needed` | [Repository](https://github.com/python-visualization/folium) |
| Cartopy | Python cartography | `docs-needed` | [Repository](https://github.com/SciTools/cartopy) |
| contextily | Python basemaps | `docs-needed` | [Repository](https://github.com/geopandas/contextily) |
| topojson/world-atlas | TopoJSON data | `archived-monitor` | [Repository](https://github.com/topojson/world-atlas) |
| amCharts Geodata | Web charting / maps | `alternative-available` | [Repository](https://github.com/amcharts/amcharts4-geodata) |
| DataHub geo-countries | Open data package | `audit-needed` | [Repository](https://github.com/datasets/geo-countries) |

## How to contribute

1. Pick one tool from the target software list.
2. Check whether its Morocco map supports the current 12-region administrative structure.
3. Identify whether the tool needs a data update, documentation, example, or extra map format.
4. If the required format does not exist in this repository, add it first for review and reuse.
5. Open an issue or PR with screenshots, version details, data source, validation output, and proposed fix.
6. If the upstream project only renders custom data, add a usage example here instead of changing upstream code.

Please keep contributions scoped, technical, reproducible, and limited to map compatibility. Do not use contributions to make political statements, remove unrelated entities, or change behavior outside the specific map being audited.

## License

This repository is released under the MIT License.

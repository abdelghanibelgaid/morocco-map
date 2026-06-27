# Contributing

Thanks for helping improve Morocco map compatibility across open-source software.

## Good contributions

- Add a new Morocco map format such as TopoJSON, GeoPackage, Shapefile, SVG, PMTiles, or MBTiles.
- Audit a software and document whether Morocco’s current 12-region structure is missing or outdated.
- Open a focused upstream issue or pull request and link it in `catalog/tools.yml`.

## Before proposing an upstream change

1. Verify whether the target project owns or bundles the map data.
2. Check the project license and geodata license requirements.
3. Confirm whether Morocco’s current 12-region structure is missing or outdated.
4. Keep the change scoped to Morocco map compatibility. Do not use contributions to make political statements, remove unrelated entities, or change behavior outside the specific map being audited.
5. Include screenshots, file paths, validation output, and a clear provenance note.

## Contribution workflow

1. Pick a tool from the README target list.
2. Audit the existing Morocco map behavior.
3. Decide the needed contribution type:
   - `audit-needed`
   - `docs-needed`
   - `format-needed`
   - `issue-open`
   - `pr-open`
   - `approved-merged`
   - `not-applicable`
4. Add or update the relevant file, example, issue, or PR.
5. Update `catalog/tools.yml`.
6. Open a pull request with a short explanation and screenshots if relevant.

## Contribution targets

Contributors can help by adding more formats and integrations:

- Shapefile
- GeoPackage
- SVG
- PMTiles / MBTiles

## Status updates

Update `catalog/tools.yml` when a tool changes status.

| Status | Meaning |
|---|---|
| `approved-merged` | Upstream PR accepted or merged |
| `audit-needed` | Tool needs technical verification before opening an issue or PR |
| `docs-needed` | Tool likely needs examples or documentation using this map |
| `format-needed` | Repository should provide an additional GIS file format |
| `issue-open` | Upstream issue has been opened |
| `pr-open` | Upstream pull request has been opened |
| `not-applicable` | Tool does not own map data or does not need a change |
| `alternative-available` | Tool already has a usable Morocco-compatible option |
| `archived-monitor` | Upstream is archived or not suitable for a direct PR |

## Pull request checklist

Before opening a PR, make sure:

- [ ] The change is scoped to Morocco map compatibility.
- [ ] The file format is documented.
- [ ] The data source or provenance is clear.
- [ ] The output was validated.
- [ ] Screenshots or examples are included when useful.
- [ ] `catalog/tools.yml` is updated if tool status changed.

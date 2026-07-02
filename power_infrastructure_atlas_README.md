# Power Infrastructure Atlas

## Files
- `power_infrastructure_atlas_v1.html` — single-file application

## How to run
Open the file in a browser, or better, serve it locally:

```bash
py -m http.server 8000
```

Then open `http://localhost:8000/power_infrastructure_atlas_v1.html`.

## What is wired live
- HIFLD transmission lines
- HIFLD substations
- HIFLD natural gas pipelines
- FRA/BTS NARN rail lines
- FHWA/BTS NHS highways
- USACE NWN waterways
- BLM/USFS Section 368 energy corridors
- WRI Aqueduct 4.0 water risk
- Global Energy Monitor integrated power
- IM3 existing data centers
- IM3 projected data centers
- Epoch frontier data centers
- AFDC EV charging stations
- OSM power via Overpass for current map extent

## What loads through the built-in source loader
- EIA-860M plant data
- Our Grid Future planned transmission data
- TeleGeography submarine cables
- Any extra CSV, XLSX, GeoJSON, KML, or zipped shapefile you want to layer in

## Key UI behavior
- Dark neon basemap and glass panels styled to match the reference image
- Left rail + floating controls
- Live layer toggles by category
- Technology, status, and search filters for plants
- Voltage legend for transmission
- Live metric cards for visible plants, MW, data centers, and transmission mileage
- Credits drawer with source attribution

## Notes
- Some public services are viewport-based and refresh as you pan/zoom.
- Heavy layers intentionally wait for closer zoom levels.
- The app is built as a single HTML file so you can edit and hand off easily.

# Union Beach Roads at Risk

Static GitHub Pages app for drawing road and cross-section profiles through the Union Beach municipal DEM.

The interface follows the North Wildwood Roads at Risk reference: threshold presets, NAVD88/MLLW conversion, terrain and hillshade views, saved multi-line cross sections, flood-history and future-frequency charts, and CSV/Shapefile exports.

Municipal constants:

- Observations: USGS 01407081, Keansburg
- PETSS / NOAA station: 8531592
- NAVD88 thresholds: 4.08 ft minor, 5.08 ft moderate, 6.08 ft major
- MLLW thresholds: 7 ft minor, 8 ft moderate, 9 ft major
- MLLW = NAVD88 + 2.92 ft

Terrain source: USGS 3DEP Bare Earth DEM Dynamic ImageServer, clipped to the Union Beach Borough boundary at 5-foot resolution.

---
title: VT NAD83 USGS Quadrangle Boundaries - corner points
created: '2020-11-12T13:06:16.983834'
modified: '2020-11-12T13:06:16.983845'
state: active
type: dataset
tags:
  - 7 5 Minute Quadrangle Edges And Tics
  - Boundaries
  - Datasetboundarytile_quad83
  - Isothemebasemap
  - Isothemeboundary
  - Nad83
  - Nodevcgi
  - Quad83
  - Subthemeother
  - Subthemetile
  - Usgs Quadrangles
  - Usgs Quads
  - Vcgi Open Data
groups: []
csv_url: >-
  https://geodata.vermont.gov/datasets/e65078dc004b4c21ab522166d0c88f30_8.csv?outSR=%7B%22latestWkid%22%3A32145%2C%22wkid%22%3A32145%7D
json_url: ''
layout: post

---
(<a href='http://maps.vcgi.vermont.gov/gisdata/metadata/BoundaryTile_QUAD83.htm' target='_blank'>Link to Metadata</a>) Generated from exact latitude-longitude coordinates and projected from Geographic coordinates (Lat/Long) NAD83 into State Plane Meters NAD83. The Arc/Info GENERATE command was used with the following parameters; generate BoundaryTile_QUAD83 fishnet no labels -73.500,42.625 -73.500,42.725 0.125,0.125 20,17 The Arc/Info project command was then used to re-project from Geographic (DD)NAD83 into Vermont State Plane Meters (NAD83). Extraneous polygons where removed. Polygon label points where transfered from the QUAD coverage into the new coverage, resulting in duplicate attribute items. The tics in this data layer should only be used for digitizing if your source data is in NAD83! Use BoundaryTile_QUAD27 if your source data is in NAD27. In both cases you should re-project this coverage into UTM before digitizing. When you've completed your digitizing work re-project the data back into Vermont State Plane Meters NAD83.

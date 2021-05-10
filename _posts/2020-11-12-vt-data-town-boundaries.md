---
title: VT Data - Town Boundaries
created: '2020-11-12T13:05:46.585964'
modified: '2020-11-12T13:05:46.585971'
state: active
type: dataset
tags:
  - Bndhash
  - Borders
  - Boundaries
  - Boundary
  - Datasetboundaryother_bndhash
  - Isothemeboundary
  - Nodevcgi
  - Subthemeother
  - Subthemetown
  - Town
  - Towns
  - Vcgi Open Data
groups: []
csv_url: >-
  https://geodata.vermont.gov/datasets/0e4a5d2d58ac40bf87cd8aa950138ae8_39.csv?outSR=%7B%22latestWkid%22%3A32145%2C%22wkid%22%3A32145%7D
json_url: ''
layout: post

---
(<a href='http://maps.vcgi.vermont.gov/gisdata/metadata/BoundaryOther_BNDHASH.htm' target='_blank'>Link to Metadata</a>) The BNDHASH dataset depicts Vermont villages, towns, counties, Regional Planning Commissions (RPC), and LEPC (Local Emergency Planning Committee) boundaries. It is a composite of generally 'best available' boundaries from various data sources (refer to ARC_SRC and SRC_NOTES attributes). However, this dataset DOES NOT attempt to provide a legally definitive boundary. The layer was originally developed from TBHASH, which was the master VGIS town boundary layer prior to the development and release of BNDHASH. By integrating village, town, county, RPC, and state boundaries into a single layer, VCGI has assured vertical integration of these boundaries and simplified maintenance. BNDHASH also includes annotation text for town, county, and RPC names. BNDHASH includes the following feature classes: 1) VILLAGES = Vermont villages 2) TOWNS = Vermont towns 3) COUNTIES = Vermont counties 4) RPCS = Vermont's Regional Planning Commissions 5) LEPC = Local Emergency Planning Committee boundaries 6) VTBND = Vermont's state boundary The master BNDHASH layer is managed as ESRI geodatabase feature dataset by VCGI. The dataset stores villages, towns, counties, and RPC boundaries as seperate feature classes with a set of topology rules which binds the features. This arrangement assures vertical integration of the various boundaries. VCGI will update this layer on an annual basis by reviewing records housed in the VT State Archives - Secretary of State's Office. VCGI also welcomes documented information from VGIS users which identify boundary errors. NOTE - VCGI has NOT attempted to create a legally definitive boundary layer. Instead the idea is to maintain an integrated village/town/county/rpc boundary layer which provides for a reasonably accurate representation of these boundaries (refer to ARC_SRC and SRC_NOTES). BNDHASH includes all counties, towns, and villages listed in &quot;Population and Local Government - State of Vermont - 2000&quot; published by the Secretary of State. BNDHASH may include changes endorsed by the Legislature since the publication of this document in 2000 (eg: villages merged with towns). Utlimately the Vermont Secratary of State's Office and the VT Legislature are responsible for maintaining information which accurately describes the location of these boundaries. BNDHASH should be used for general mapping purposes only. * Users who wish to determine which boundaries are different from the original TBHASH boundaries should refer to the ORIG_ARC field in the BOUNDARY_BNDHASH_LINE (line featue with attributes). Also, updates to BNDHASH are tracked by version number (ex: 2003A). The UPDACT field is used to track changes between versions. The UPDACT field is flushed between versions.

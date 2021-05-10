---
title: VT Data - Voting Tabulation Areas per Decennial Redistricting 2012
created: '2020-11-12T13:06:07.213813'
modified: '2020-11-12T13:06:07.213824'
state: active
type: dataset
tags:
  - Datasetboundaryother_votetab2012
  - Election
  - Isothemeboundary
  - Nodevcgi
  - Poll
  - Subthemeother
  - Vcgi Open Data
  - Vote
  - Voting
groups: []
csv_url: >-
  https://geodata.vermont.gov/datasets/f801723757654cb4b06dccef1a64ae99_41.csv?outSR=%7B%22latestWkid%22%3A32145%2C%22wkid%22%3A32145%7D
json_url: ''
layout: post

---
(<a href='http://maps.vcgi.vermont.gov/gisdata/metadata/BoundaryOther_VOTETAB2012.htm' target='_blank'>Link to Metadata</a>) This layer represents the smallest voting tabulation area. In some cases, the geographic extent is a municipality, in other cases it is a section of a municipality. Many of the polygons in this layer represent PART of a state House district (the House District is the unit to which votes are tabulated to actually determine the winner of an election, and many of them are multi-town). An inherent problem in creating this layer was the lack of spatial congruence between the HOUS2012 layer and the TWNBNDS layer. Although in many cases parts of the HOUS2012 layer purport to follow town boundaries (according to the statute where they are verbally described) the data layer that was used to create the data was not the TWNBNDS layer, but likely a Census Tiger Files layer. This Voting Tabulation layer was created using aspects of the two existing layers: Town Boundaries from the TWNBNDS layer, whereas any boundaries that split towns were derived from the HOUS2012 layer. The Process Steps section below describes how this was achieved, and how district labels were assigned to new polygons.

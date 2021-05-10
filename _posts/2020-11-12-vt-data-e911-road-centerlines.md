---
title: VT Data - E911 Road Centerlines
created: '2020-11-12T13:06:12.686252'
modified: '2020-11-12T13:06:12.686262'
state: active
type: dataset
tags:
  - Datasetemergencye911_rds
  - E911
  - Emergency
  - Isothemeemergency
  - Isothemetrans
  - Newnessupdated
  - Nodevcgi
  - Road Centerlines
  - Roads
  - Subthemee911
  - Subthemeroad
  - Vcgi Open Data
groups: []
csv_url: >-
  https://geodata.vermont.gov/datasets/c8c147a0f76e4b51ad23f7d02cff5b05_23.csv?outSR=%7B%22latestWkid%22%3A32145%2C%22wkid%22%3A32145%7D
json_url: ''
layout: post

---
(<a href='http://maps.vcgi.vermont.gov/gisdata/metadata/EmergencyE911_RDS.htm' target='_blank'>Link to Metadata</a>) REFRESHED WEEKLY. EmergencyE911_RDS was originally derived from RDSnn (now called TransRoad_RDS). &quot;Zero-length ranges&quot; in the ROADS layer pertain to grand-fathered towns that have not yet provided the Enhanced 9-1-1 Board road segment range information. RDSnn was originally developed using a combination of paper and RC Kodak RF 5000 orthophotos (visual image interpretation and manual digitizing of centerlines). Road attributes (RTNO and CLASS) were taken from the official VT Agency of Transportation (VTrans) highway maps. New roads not appearing on the photos were digitized with locations approximated from the VTrans highway maps. State Forest maps were used to determine both location and attributes of state forest roads. Some data updates have used RF 2500 or RF 1250 orthophotos and GPS, or other means for adding new roads and improving road locations. The Enhanced E911 program added new roads from GPS and orthos between 1996-1998. Also added road name and address geocoding. VCGI PROCESSING (Tiling and Added items); E911 provides the EmergencyE911_RDS data to VCGI in a statewide format. It lacks FIPS6 coding, making it difficult to extract data on the basis of town/county boundaries. As a result, VCGI has added FIPS6 to the attribute table. This field was originally populated by extracting MCODE value from RDNAME and relating to TBPOLY.PAT to bring over matching MCODE values. FIPS6 problems along the interstates and &quot;Gores &amp; Grants&quot; in the Northeast Kingdom, were corrected. All features with an MCODE equal to 200 or 579 were assigned a FIPS6 equal to 0. The center point of these arcs were then intersected with BoundaryTown_TBHASH to assign a FIPS6 value. This information was then transfered back into the RDS.AAT file via a relate. A relate was established between the ROADNAMES.DBF file (road name lookup table) and the RDS.AAT file. The RDFLNAME attribute was populated by transfering the NAME value in the ROADNAMES.DBF table. The RDFLNAME item was then parsed into SUF.DIR, STREET.NAME, STREET.TYPE, and PRE.DIR, making addressing matching functions a little easier. See the &quot;VT Road Centerline Data FAQ&quot; for more information about TransRoad_RDS and EmergencyE911_RDS. http://vcgi.vermont.gov/techres/?page=./white_papers/default_content.cfm

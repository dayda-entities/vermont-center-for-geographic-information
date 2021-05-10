---
title: VT Data - Drive Test Verizon
created: '2020-11-12T13:10:40.791991'
modified: '2020-11-12T13:10:40.792001'
state: active
type: dataset
tags:
  - Datasetutilitytelecom_drivetest
  - Datayear2018
  - Isothemeutility
  - Nodevtpsd
  - Subthemetelecom
  - Telecommunications
groups: []
csv_url: >-
  https://geodata.vermont.gov/datasets/4a5d4510f1c642679329c1a4accff1af_12.csv?outSR=%7B%22latestWkid%22%3A32145%2C%22wkid%22%3A32145%7D
json_url: ''
layout: post

---
<div>This dataset contains mobile wireless download speed test results and areas where the PSD (Vermont Public Service Department) challenged mobile wireless service asserted by wireless carriers.<p></p>DOWNLOAD SPEED TEST RESULTS</div><div>Results from download speed tests that were conducted in September-December 2018 are contained by 6 point feature-classes, each with results for a particular carrier.<p></p>PSD staff employed the android smartphone application G-NetTrack to conduct download speed tests at approximately 300 meter intervals along all federal-aid highways.<p></p>The point feature-classes are very detailed and more suitable when zoomed into the neighborhood scale. All point feature-classes have the same field schema, which includes these fields:</div><div> timestamp: Date and time at which the data point was collected.<p></p> signal_str: Signal strength (RSRP in dBm).<p></p> download_s: Download speed (in Mbps).<p></p> latency: The round-trip time for a request to a website, in milliseconds.<p></p>DRIVE-TEST BLOCKS</div><div>Drive-test blocks (Utility_DriveTest_poly_Blocks) is a polygon feature-class that is composed of 1-kilometer blocks; it has a field for each of the 6 carriers; the fields show the average download speed recorded in each block for each carrier.<p></p>The fields also include a composite field (All_) that contains averages of all carriers, masking variation in coverage between individual carriers. "999" indicates no test was conducted for the carrier in that block.<p></p>Drive-test blocks are generalized information and are suitable when zoomed at various scales. A BLOCK DOES NOT INDICATE SERVICE THROUGHOUT A BLOCK; use the point feature-classes for detailed data and judge accordingly.<p></p>WIRELESS CHALLENGE BLOCKS</div><div>Wireless Challenge Blocks (Utility_DriveTest_poly_VTMFCIIChallengeBlocks) depicts the status of each block in the submission of the PSD in the FCC Mobility Fund Phase II Challenge process. It shows challenges to mobile wireless service asserted by wireless carriers<p></p>A value of 0 in the Area_1 field indicates that the challenge was rejected, either because a) the block is already largely eligible, or b) because no tests below 5 Mbps were submitted.<p></p>DISCLAIMER</div><div>VCGI and the State of VT make no representations of any kind, including but not limited to the warranties of merchantability or fitness for a particular use, nor are any such warranties to be implied with respect to the data.<p></p></div><div></div>

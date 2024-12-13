---
title: Other Information
lastmod: "2024-01-15"
---
The ship’s real-time feed of position, time, temperature, salinity is broadcast either over the ship’s network and recorded by the SeaFlow computer.
<!--more--> 
Additional data streams from the SeaFlow instrument, such as sample stream pressure and event rate are also recorded. The format of the underway data differs among ships, so we use custom scrips to convert/curate the ship data into a format recognized by our analysis software. 

[Click here to access the original data](https://github.com/seaflow-uw/seaflow-sfl)

Each SFL file contains the following information:

* FILE: SeaFlow filename
* DATE: data and time in GMT
* FILE DURATION: acquisition time (sec)
* LAT: latitude (deg N)
* LON: longitude (deg W)
* CONDUCTIVITY: seawater conductivity (s/m)
* SALINITY: seawater salinity (psu)
* OCEAN TEMP: seawater temperature (deg C)
* PAR: Photosynthetic Active Radiations above surface water (µmol/m2/s)
* BULK RED: bulk red fluorescence measured by SeaFlow (unitless)
* STREAM PRESSURE: pressure of the sample line (psi), usually set at 12, which can then be converted to sample flow rate (mL min-1)
* EVENT RATE: number of events (i.e., particles) recorded per second (should be below 18,000 for quality data) by SeaFlow

Any other data not broadcasted during the cruise can be retrieved later from the [Rolling Deck to Repository](https://www.rvdata.us/) (R2R).

List of datasets and associated cruise and geolocation metadata.

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vT76VR2_VAulc6caxklUqOTOj_7EEnNJiFlHqaD1fC7Pc_zqw5i7wwcQUcDa8dtALZXoVHt2t0mdPS5/pubhtml?widget=true&amp;headers=false" width=700 height=1000></iframe>

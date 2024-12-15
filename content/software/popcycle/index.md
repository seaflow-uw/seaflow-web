---
title: popcycle
date: "2014-12-01"
show_date: false
share: false
---
An R package that offers a reproducible approach to process, calibrate and curate flow cytometry data collected by SeaFlow. 
<!--more--> 
 The software package performs 3 key analyses
1. **gating**: Classification of phytoplankton cell populations using a mixture of manual gating and a semi-supervized clusterting algorithm. This involves identifying and classifying different phytoplankton populations, such as *Prochlorococcus*, *Synechococcus*, and *Crocosphaera*, based on their optical properties (forward scatter, chlorophyll fluorescence, and phycoerythrin fluorescence).
2. **light scatter conversion**: Convert light scattering of each particle to cell diameter ([fsc-size-calibration](https://github.com/seaflow-uw/fsc-size-calibration)) and carbon content ([fsc-poc-calibration](https://github.com/seaflow-uw/fsc-poc-calibration)).This is achieved by applying Mie light scattering theory to a simplified optical model and using an optimization procedure to minimize differences between measured forward scatter and the scatter intensity predicted by Mie light scatter of homogeneous spherical particles
3. **population data**: Perform aggregate statistics along with error propagation for the different populations.This includes calculating cell abundance, median, 25th and 75th percentiles of optical properties, equivalent spherical diameter (ESD), and carbon quotas for each population, along with measurement errors based on uncertainties in the virtual core volume and light scatter conversion. 

The cell population label, diameter and carbon content of each particle are saved as separate text files with a similar file structure as the raw data. The metadata, gating scheme, and aggregated statistics for each step are saved to a SQL database using SQLite3.

Description of the model is available here: https://doi.org/10.1038/s41597-019-0292-2

Code is available here: https://github.com/seaflow-uw/popcycle
---
title: High-Resolution Ocean Observations
date: "2022-06-01"
show_date: false
share: false
---

SeaFlow provides high-resolution data on the abundance, size, and optical properties of phytoplankton populations.    

<!--more-->
SeaFlow data are processed using 3 key steps: filtration, classification, and data conversion.  The filtration step identifies particles in focus, and the classification step categorizes particles based on optical properties.  The data sets are then expanded to include equivalent spherical diameter (ESD) and carbon quotas derived from light scatter measurements.  ESD was estimated by applying Mie light scattering theory to a combination of flow cytometry calibration beads and cultured organisms of determined size. 

SeaFlow collects the following **state estimate** data:
  * **Abundance**: SeaFlow measures the concentration of different phytoplankton populations in the water.  This data helps track changes in the abundance and distribution of these organisms over space and time, providing insights into the factors influencing their growth and survival.   
  * **Size**: The instrument determines the size of individual phytoplankton cells by analyzing their light scatter properties.  This information is used to classify cells into different size categories, which is important because phytoplankton size influences their ecological roles and contribution to biomass.    
  * **Optical Properties**: SeaFlow measures the fluorescence emitted by phytoplankton cells, providing information about the pigments they contain.  These pigments, such as chlorophyll a and phycoerythrin, are used for photosynthesis and can be used to distinguish different phytoplankton groups.    
  * **Equivalent Spherical Diameter (ESD)** : This is a measure of cell size based on light scatter, assuming the cell is a sphere.    
  * **Carbon Quotas**: This estimate is derived from the ESD and provides information about the biomass of phytoplankton communities.
  * **Carbon biomass**: This is the carbon content multiplied by cell abundance.

And the following **rate estimate** data:
  * **Cellular Growth Rate**:  Leveraging time-series data analysis, this rate is calculated from the daytime rate of change in carbon quotas over time. Time-series data analysis techniques, such as time decomposition analysis, are applied to the carbon quota measurements collected over time to estimate the net cellular growth rate.
  * **Net Production**:  Building upon the cellular growth rate and carbon biomass, net production is calculated by multiplying these two state estimate parameters. This multiplication provides an estimate of the overall carbon production by the phytoplankton community, considering both the growth rate of individual cells and the total biomass present.


**Learn More**:
For a deeper understanding of SeaFlow's data, please refer to these two articles: 
* State estimation: https://doi.org/10.1038/s41597-019-0292-2
* Rate estimation: https://doi.org/10.1002/lno.12683

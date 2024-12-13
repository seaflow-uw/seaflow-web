---
title: CytoSegmenter
date: "2020-11-01"
---
[Cytosegmenter](https://github.com/cjones6/cytosegmenter) is a kernel-based change detection method to map shifts in phytoplankton communities measured by flow cytometry. Detailed information can be found in [Jones et al. (2020)](https://doi.org/10.1111/2041-210X.13647).
<!--more--> 
In this project in collaboration with Dr. Corinne Jones and UW Pr. Zaid Harchaoui, we applied a new method to segment flow cytometry data on phytoplankton measured during research cruises. Understanding how phytoplankton communities vary in time and space across ocean basins is critical for predicting how marine ecosystems will respond to future climate change. We propose an approach to segmenting sequences of point clouds into distinct segments. The software first generates Hilbertian embeddings for each point cloud. It then segments the data by applying a kernel-based change-point detection method on the embeddings. To estimate the number of change points we propose using auxiliary labeled data.
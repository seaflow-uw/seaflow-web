---
title: cytosegmenter
date: "2021-11-01"
show_date: false
share: false
---
A kernel-based change detection method to map shifts in phytoplankton communities measured by flow cytometry. 

<!--more--> 
In this project in collaboration with Dr. Corinne Jones and UW Pr. Zaid Harchaoui, we applied a new method to segment flow cytometry data on phytoplankton measured during research cruises. Understanding how phytoplankton communities vary in time and space across ocean basins is critical for predicting how marine ecosystems will respond to future climate change. We propose an approach to segmenting sequences of point clouds into distinct segments. The software first generates Hilbertian embeddings for each point cloud. It then segments the data by applying a kernel-based change-point detection method on the embeddings. To estimate the number of change points we propose using auxiliary labeled data.

Description of the model is available here: https://doi.org/10.1111/2041-210X.13647

Code is available here: https://github.com/seaflow-uw/cytosegmenter 
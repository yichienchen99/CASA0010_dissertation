# Exploring the spatial distribution of cycle accessibility

## A data-informed approach to London’s sustainable transport strategy

This repository documents the data processing and analysis for CASA0010 Dissertation, which set out to answer the following research question:

*How can cycle accessibility in London be measured spatially?*

To reproduce the study, run the files in order (The produced datasets that will be used in other files are saved as CSV so it is recommended to clean the R environment to save memory): 

1. 1_data_processing.Rmd (collect and clean the data inputs)
2. 2_london_CAL.Rmd (estimate travel time using r5r engine and compute access index)
3. 3_london_CAL_cont.Rmd (convert access index into Cycle Access Level and analyse the spatial patterns of CAL and PTAL)
4. 4_MCDA.Rmd (visualise some contexts for the CAL outcomes, including elevation, population density, road network and cycle parking capacity)

The above files can already produce the dissertation outputs. The following files give additional information on some sections that could be run optionally. 

1. cycle_infra.Rmd (compare OSM data with the CID cycle lanes)
2. study_area.Rmd (visualise London borough boundaries and sampled grid cells)
   
Some data obtains large file size, not uploaded in this repo, but instructions on access to those files can be found in the code. 

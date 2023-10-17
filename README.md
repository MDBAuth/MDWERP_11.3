# MDWERP_11.3
Theme 3 - Environmental Outcomes / Project 11.3: Predicting change in floodplain habitat availability at the Basin scale


## Project_113_2022_reboot_loop.ipynb

This notebook outputs innundation data which will be used for MD-WERP Strategic Project 11.3.

It access Landsat data from Google Earth Engine and calculates monthly maximum inundation (as well as clear dry areas and "bad" areas). 
The outputs are CSVs.

## Project_113_QA.ipynb

This notebook does 3 different processes:
1. Compares area of contracted catchments as calculated in ArcMap to the area of contracted catchments as calculated in GEE 
(i.e. the sum of all areas per ANAE type)
2. Accesses and concatenates all CSV outputs from GEE.
3. Plots the innundation for a given catchment and ANAE type.

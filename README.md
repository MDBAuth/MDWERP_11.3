# MD WERP Project 11.3
## Background

The Murray–Darling Water and Environment Research Program (MD-WERP) is a 4-year, $20 million Australian Government initiative to strengthen scientific knowledge of the Murray–Darling Basin through generating new knowledge, innovation and tools. For more ifnormation see https://getinvolved.mdba.gov.au/murray-darling-water-and-environment-research-program

Project 11.3 'Predicting change in floodplain habitat availability at the Basin scale' aims to understand the relationships between flow, rain, and other catchment variables and how they may impact floodplain inundation and therefore habitat availability. These relationships can be used to predict inundation under different flow scenarios. The outcomes of this project will benefit environmental flow management in the Murray-Darling Basin at a whole of Basin scale. 

The objectives of this project were to first, use Landsat imagery to quantify basin wide floodplain inundation in different habitat types, over a 30-year period. The second objective was to develop a statistical technique to uncover relationships between floodplain inundation, flow, rainfall, and other catchment variables. The third objective was to use these relationships to predict floodplain inundation under different climate change and management flow scenarios.  

This repository contains the codes used to produce the inundation data, and a code the help QA the results.

## Project_113_2022_reboot_loop.ipynb

This notebook outputs innundation data used for MD-WERP Strategic Project 11.3.

It access Landsat data from Google Earth Engine and calculates monthly maximum inundation (as well as clear dry areas and bad areas). 
The outputs are CSVs.

## Project_113_QA.ipynb

This notebook does 3 different processes:
1. Compares area of contracted catchments as calculated in ArcMap to the area of contracted catchments as calculated in GEE 
(i.e. the sum of all areas per ANAE type)
2. Accesses and concatenates all CSV outputs from GEE.
3. Plots the innundation for a given catchment and ANAE type.

# Data_Visualization_Portfolio

## Pacific Northwest Stream Temperature Shiny App

A major heatwave struck the Pacific Northwest in June 2021, breaking many temperature records. This not only made it difficult for people to stay cool, it also caused issues for fish. Stream temperatures in many locations within the Colombia River Basin grew warmer than 68F - a critical threshold for salmon. At stream temperatures over this threshold, salmon experience great stress and are more likely to contract diseases or die. Heat-related salmon mortality was recorded in the region as a result of the 2015 and 2021 heat waves. 

Interactive App [link](https://laurapuckett.shinyapps.io/Pacific_NW_Stream_Temperature_during_2021_Heatwave/) and Code Repository [link](https://github.com/Laura-Puckett/Stream_Temperature)


| ![](https://github.com/Laura-Puckett/Stream_Temperature/blob/main/screenshots/Screen%20Recording.gif) | 
|:--:| 
| Demo of Shiny app|


## Comparing spaceborne LiDAR datasets [Code repository](https://github.com/Laura-Puckett/lidar_comparisons)

This workflow is intended for comparing gedi, icesat-2, or both against airborne lidar data for an area. Because Icesat-2 and GEDI can't be compared directly against each other (due to mismatch in size/shape of footprints), comparing them against airborne lidar separately is used here to infer how similar they are to each other. The workflow is currently set up to run on a computing cluster, because building the geometries that represent each spaceborne lidar footprint and then extracting the intersecting airborne lidar values is computationally intensive. Processes are automated to run from a single bash script. 

This workflow downloads the icesat-2 data, but assumes that you already have gedi and airborne lidar downloaded (unless using NEON lidar - there is a script for that)

| ![](https://github.com/Laura-Puckett/lidar_comparisons/blob/main/gedi_icesat2_als_comparison.png) | 
|:--:| 
| *Example output comparing GEDI and Icesat-2 for a site in the Sierra Nevada Mountains* |

# Data_Visualization_Portfolio

## Pacific Northwest Stream Temperature Shiny App

A major heatwave struck the Pacific Northwest in June 2021, breaking many temperature records. This not only made it difficult for people to stay cool, it also caused issues for fish. Stream temperatures in many locations within the Colombia River Basin grew warmer than 68F - a critical threshold over which salmon experience great stress and are more likely to contract diseases or die. Heat-related salmon mortality was recorded in the region as a result of the 2015 and 2021 heat waves. 

In this project, I displayed stream temperatures from USGS stations within the Pacific Northwest in an interactive app. 

Interactive App [link](https://laurapuckett.shinyapps.io/Pacific_NW_Stream_Temperature_during_2021_Heatwave/) and Code Repository [link](https://github.com/Laura-Puckett/Stream_Temperature)


| ![](https://github.com/Laura-Puckett/Stream_Temperature/blob/main/screenshots/Screen%20Recording.gif) | 
|:--:| 
| Demo of Shiny app|


## Comparing spaceborne LiDAR datasets 
Code repository [link](https://github.com/Laura-Puckett/lidar_comparisons)

This workflow is intended for comparing GEDI, ICESat-2, or both against airborne LiDAR data for an area. Steps include downloading data, building geometries for each spaceborne lidar footprint, extracting the intersecting airborne LiDAR values, and plotting results.  The workflow was built to run on a computing cluster, because the process is computationally intensive for datasets of this size. 

| ![](https://github.com/Laura-Puckett/lidar_comparisons/blob/main/gedi_icesat2_als_comparison.png) | 
|:--:| 
| *Example output comparing GEDI and Icesat-2 for a site in the Sierra Nevada Mountains* |

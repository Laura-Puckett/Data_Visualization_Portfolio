# Data_Visualization_Portfolio

## Pacific Northwest Stream Temperature Shiny App 

### [Link to the interactive app](https://laurapuckett.shinyapps.io/Pacific_NW_Stream_Temperature_during_2021_Heatwave/)


| ![](https://github.com/Laura-Puckett/LauraPuckett_Portfolio/blob/main/Screen%20Shot%202021-11-21%20at%2010.43.51%20PM.png) | 
|:--:| 
| An interactive map containing clickable USGS station locations|

| ![](https://github.com/Laura-Puckett/LauraPuckett_Portfolio/blob/main/Screen%20Shot%202021-11-21%20at%2010.32.13%20PM.png) | 
|:--:| 
| A plot of data for all sites, with the selected USGS station highlighted in black. |

| ![](https://github.com/Laura-Puckett/LauraPuckett_Portfolio/blob/main/Screen%20Shot%202021-11-21%20at%2010.32.33%20PM.png) | 
|:--:| 
| Data from the selected USGS station plotted by year with major heatwave years highlighted. |

## [Comparing spaceborne LiDAR datasets](https://github.com/Laura-Puckett/lidar_comparisons)
This workflow is intended for comparing gedi, icesat-2, or both against airborne lidar data for an area. Because Icesat-2 and GEDI can't be compared directly against each other (due to mismatch in size/shape of footprints), comparing them against airborne lidar separately is used here to infer how similar they are to each other. The workflow is currently set up to run on a computing cluster, because building the geometries that represent each spaceborne lidar footprint and then extracting the intersecting airborne lidar values is computationally intensive. Processes are automated to run from a single bash script. 

This workflow downloads the icesat-2 data, but assumes that you already have gedi and airborne lidar downloaded (unless using NEON lidar - there is a script for that)

| ![](https://github.com/Laura-Puckett/lidar_comparisons/blob/main/gedi_icesat2_als_comparison.png) | 
|:--:| 
| *Example output comparing GEDI and Icesat-2 for a site in the Sierra Nevada Mountains* |

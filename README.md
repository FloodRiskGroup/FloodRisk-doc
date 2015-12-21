# FloodRisk-doc
This repository contains sample data to test the plugin FloodRisk
# Data
The data consist of:
- a digital elevation model (DEM) : DEM.tif
- results of a flood simulation with 2D model
  - map of maximum water depth values due to flooding
  - map of maximum velocity values due to flooding
  - map of warning time
- population census map
  - Census Data Layer: Polygon Vector having fields **CensID** type *Real*; **Resident** type *Integer*
- data of assets at risk
  - Property Polygon Vector Layer having fields **OccuType** type *VARCHAR(5)*; **Valstr** type *Real*; **Valcon** as *Real*
  - Infrastructures Line Vector Layer having fields **OccuType** type *VARCHAR(5)*; **Valstr** type *Real*; **Valcon** as *Real*
- data of their vulnerability (depth-damage curves)
  - 2 depth-damage curve for each **OccuType** : 1 for structure and 1 for content

**Valstr**: unit value of the structure

**Valcon**: unit value of content

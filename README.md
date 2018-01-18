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

Below you can find the link to some papers about FloodRisk:

Albano, R., Mancusi, L., Sole, A., Adamowski, J., 2017. FloodRisk: a collaborative free and open-source software for flood risk analysis, Volume 8, Iss. 2, pp. 1812-1832, 2017
http://www.tandfonline.com/doi/full/10.1080/19475705.2017.1388854

Albano, R., Mancusi, L. and Abbate, A., 2017. Improving Flood Risk Analysis for effectively supporting the implementation of flood risk management plans: the case study of “Serio” Valley, Environmental Science and Policy, Volume 75, pp. 158-172
http://www.sciencedirect.com/science/article/pii/S1462901116309728
 
Albano, R., Craciun, I., Mancusi, L., Sole, A., Ozunu, A., 2017. Flood damage assessment and uncertainty analysis: the case study of 2006 flood in Ilisua Basin in Romania, Carpathian Journal of Earth and Environmental Sciences Volume 12, Number 2, pp. 335-346
http://www.ubm.ro/sites/CJEES/viewTopic.php?topicId=683
 
Albano, R., Mancusi, L., Sole, A., Adamowski, J., 2015. Sustainable and collaborative strategies for EU flood risk management: FOSS and Geospatial Tools – challenge and opportunities for operative risk analysis, ISPRS Int. J. Geo-Inf., Volume 4, pp. 2704-2727
http://www.mdpi.com/2220-9964/4/4/2704
 

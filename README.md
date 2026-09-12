# GRASS GIS Scripts — Landsat TM Raster Calculations and LST Mapping of Qingdao, China

GRASS GIS shell scripts used to produce the figures in the peer-reviewed article by Polina Lemenkova. The scripts analyse Landsat TM/ETM+ imagery of Qingdao, China (2004 and 2009) by raster calculations: land-surface-temperature retrieval, colour composites, terrain derivatives, DEM handling and image fusion.

**Published in:** *Tehnički vjesnik / Technical Gazette* **2022**, *29*(6), 1956–1963
**DOI:** https://doi.org/10.17559/TV-20220322091846
**Journal (open access):** https://hrcak.srce.hr/284911
**HAL:** https://hal.science/hal-03834515
**Zenodo:** https://doi.org/10.5281/zenodo.7264665
**SSRN:** https://ssrn.com/abstract=4262243

## Contents
GRASS GIS shell scripts using r.in.gdal (Landsat TM band import), r.mapcalc (map algebra: radiance-to-temperature conversion for land-surface temperature), d.rgb / colour composites, r.slope.aspect (slope, aspect and curvature), DEM processing and image fusion, with cartographic display via r.colors, d.rast and d.legend. Land-surface-temperature scripts cover the 2004 and 2009 scenes.

## LaTeX source
The LaTeX source (prose) of this article is in a separate repository: https://github.com/paulinelemenkova/grass-raster-lst-slope-aspect

## Citation
Lemenkova, P. GRASS GIS Scripts for Satellite Image Analysis by Raster Calculations Using Modules r.mapcalc, d.rgb, r.slope.aspect. *Tehnički vjesnik* **2022**, *29*(6), 1956–1963. https://doi.org/10.17559/TV-20220322091846

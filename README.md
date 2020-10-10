[![DOI](https://zenodo.org/badge/261209006.svg)](https://zenodo.org/badge/latestdoi/261209006)
[![GitHub issues](https://img.shields.io/github/issues/acoiman/lulc_zamora_1986_2016?style=plastic)](https://github.com/acoiman/lulc_zamora_1986_2016/issues)
[![GitHub forks](https://img.shields.io/github/forks/acoiman/lulc_zamora_1986_2016?style=plastic)](https://github.com/acoiman/lulc_zamora_1986_2016/network)
[![GitHub stars](https://img.shields.io/github/stars/acoiman/lulc_zamora_1986_2016?style=plastic)](https://github.com/acoiman/lulc_zamora_1986_2016/stargazers)
[![GitHub license](https://img.shields.io/github/license/acoiman/lulc_zamora_1986_2016?style=plastic)](https://github.com/acoiman/lulc_zamora_1986_2016/blob/master/LICENSE)
[![Twitter](https://shields-staging.herokuapp.com/twitter/url?style=social&url=https%3A%2F%2Fgithub.com%2Facoiman%2Flulc_zamora_1986_2016)](https://twitter.com/intent/tweet?text=Wow:&url=https%3A%2F%2Fgithub.com%2Facoiman%2Flulc_zamora_1986_2016)
[<img src="https://acoiman.github.io/opendata.png" style="width: 40px" />](https://www.cos.io/initiatives/badges)

![](https://acoiman.github.io/opendata.png | width=50)

![](https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png | width=100)

## Shoreline evolution of Valencia lake and land use and land cover changes in Zamora municipality, Aragua state, Venezuela, period 1986-2016

> **Research Article:  https://doi.org/10.30897/ijegeo.734872**

------

#### **Abstract**

Understanding the current and past state of land use and land cover (LULC) changes in a region is possible through multitemporal remote sensing studies in order to identify patterns of long-term changes. This study was conducted to evaluate the shoreline dynamics of the Valencia lake and the magnitude of LULC changes in Zamora Municipality, Venezuela from 1986 to 2016. Landsat (5, 7, and 8) images were processed and classified through the object-based approach. The image classification assessment was performed through the stratified random sampling and the unbiased accuracy assessment methods over 397 sampling units. We used GIS (Geographical Information System) analysis to estimate the magnitude of LULC changes, ascertain the evolution of the shoreline, and identify areas in conflict with the potential for agricultural use. Our image classification accuracy was 69%. We found that scrublands and farmlands experienced reductions, 13029 ha, and 818 ha respectively, whereas forest, built-up, and water bodies showed increments, 11792 ha, 1482 ha, and 634 ha correspondingly. The lake shoreline underwent more than 50% of its raising during the last two study years (2003-2016). It was also observed during these two years that LULC changes prompted conflicts with other land uses, 82% of the lands affected by the shoreline increment were farmlands with high potential for crop yields, and built-up areas grew at a rate of 81 ha /yr. wherein more than one third were lands with high or moderate potential for agricultural use. Our results show that scrublands and/or grasslands experienced important reductions and to a lesser degree farmlands. On the other hand, other classes experienced remarkable increments: forest, and built-up. An upward trend of the Valencia lake shoreline was determined. Further studies are advisable to determine whether the object-based or the pixel-based classification is more suitable to evaluate LULC changes in our study area.

<div id="dot" align='center'>. . . .</div>

This repo contains the code and data of this research article. The content of the folders is as follows:

- [**accuracy_assessment**](https://github.com/acoiman/lulc_zamora_1986_2016/tree/master/accuracy_assessment): contains the input data used to classify the image of the year [2016](https://github.com/acoiman/lulc_zamora_1986_2016/tree/master/lulc/results/2016), as well as the output data resulting from the image classification.
- [**lulc**](https://github.com/acoiman/lulc_zamora_1986_2016/tree/master/lulc):  contains the results in [shapefile](https://en.wikipedia.org/wiki/Shapefile) and [geojson](https://geojson.org/) format of [Landsat](https://landsat.gsfc.nasa.gov/) image classification in Zamora municipality, Aragua state, Venezuela, from 1986 to 2016 following the [Corine Land Cove](https://land.copernicus.eu/pan-european/corine-land-cover)r schema.
- [**maps_pdf**](https://github.com/acoiman/lulc_zamora_1986_2016/tree/master/maps_pdf): contains maps in PDF format of [Landsat](https://landsat.gsfc.nasa.gov/) image classification in Zamora municipality, Aragua state, Venezuela, from 1986 to 2016 following the [Corine Land Cove](https://land.copernicus.eu/pan-european/corine-land-cover)r schema.
- [**miscellaneous**](https://github.com/acoiman/lulc_zamora_1986_2016/tree/master/miscellaneous): contains the administrative boundaries of [Zamora municipality](https://en.wikipedia.org/wiki/Zamora_Municipality,_Aragua) and [shapefiles](https://en.wikipedia.org/wiki/Shapefile) used to assign class by thematic layer in each [eCognition](https://geospatial.trimble.com/products-and-solutions/ecognition) project.
- [**rulesets**](https://github.com/acoiman/lulc_zamora_1986_2016/tree/master/rulesets): contains [eCognition](https://geospatial.trimble.com/products-and-solutions/ecognition) rule sets applied for classifying [Landsat](https://landsat.gsfc.nasa.gov/) images in Zamora municipality, Aragua state, Venezuela, from 1986 to 2016 following the [Corine Land Cove](https://land.copernicus.eu/pan-european/corine-land-cover)r schema.
- [**sisdelav_data**](https://github.com/acoiman/lulc_zamora_1986_2016/tree/master/sisdelav_data): contains the [SISDELAV](http://saber.ucv.ve/ojs/index.php/rev_venes/article/view/1092/1021) data used in this study.

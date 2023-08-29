# awesome-planetary-geology
Awesome list of planetary geology and mapping tools, repos, services and websites

Table of Contents
=================

- [awesome-planetary-geology](#awesome-planetary-geology)
- [Table of Contents](#table-of-contents)
  - [Planetary data processing and basemaps](#planetary-data-processing-and-basemaps)
  - [Web services and web (base) maps](#web-services-and-web-base-maps)
  - [Libraries and tools for planetary mapping data access and analysis](#libraries-and-tools-for-planetary-mapping-data-access-and-analysis)
  - [Planetary geologic mapping tools and aids](#planetary-geologic-mapping-tools-and-aids)
  - [Tool directories](#tool-directories)
  - [Community support](#community-support)
  - [Planetary geologic mapping - programs and meetings](#planetary-geologic-mapping---programs-and-meetings)
  - [Planetary geologic mapping products](#planetary-geologic-mapping-products)
  - [Training workshops and schools](#training-workshops-and-schools)
  - [Tutorials](#tutorials)
  - [Spectral data and processing](#spectral-data-and-processing)
  - [Visualization tools and plugins](#visualization-tools-and-plugins)
  - [Generic Processing tools](#generic-processing-tools)

## Planetary data processing and basemaps 

* USGS Astrogeology - https://github.com/USGS-Astrogeology
  * USGS ISIS - https://isis.astrogeology.usgs.gov, [GitHub](https://github.com/DOI-USGS/ISIS3)
* NASA ASP - https://ti.arc.nasa.gov/tech/asr/groups/intelligent-robotics/ngt/stereo/, [GitHub](https://github.com/NeoGeographyToolkit/StereoPipeline/)

## Web services and web (base) maps
* ASU JMARS - https://jmars.mars.asu.edu
* NASA Solar System Treks - https://trek.nasa.gov
* NASA MMGIS - https://mars.nasa.gov/maps/
* ACT-REACt Quickmap - http://quickmap.lroc.asu.edu/
* USGS/NASA Published [Interactive Geologic Maps](https://www.usgs.gov/special-topics/planetary-geologic-mapping/interactive-planetary-maps) 
* USGS [WMS Map Layers](https://astrowebmaps.wr.usgs.gov/webmapatlas/Layers/maps.html)
* ASU LROC WMS services - http://wms.lroc.asu.edu
* USGS PILOT - https://pilot.wr.usgs.gov/
* USGS POW - https://astrocloud.wr.usgs.gov/index.php?view=pow
  * see Hare (2014) - [LPSC abstract](https://www.hou.usra.edu/meetings/lpsc2014/pdf/2474.pdf)
* MarSI - https://emars.univ-lyon1.fr/MarsSI/
  * see Quantin et al. (2018) - [paper](https://doi.org/10.1016/j.pss.2017.09.014)
* MUTED - https://muted.wwu.de
  * see Heyer et al. (2018) - [paper](https://doi.org/10.1016/j.pss.2018.04.015)
  * see [LPSC 2021 poster](https://lpsc2021.ipostersessions.com/?s=2B-4F-E6-05-BE-A2-7E-7E-C8-67-C5-7F-33-20-0A-F4)
   
## Libraries and tools for planetary mapping data access and analysis 

* PlanetaryPy - https://planetarypy.org
* Planetary Data Reader (pdr) - https://github.com/millionconcepts/pdr
* SpicePy - https://github.com/AndrewAnnex/SpiceyPy
* GDAL/OGR (and Rasterio) -[Introduction](https://github.com/pds-data-dictionaries/ldd-cart/wiki/Introduction-to-Planetary-Updates-and-Tips-for-using-GDAL-3.x), [GitHub](https://github.com/OSGeo/gdal)
* sharpy (experimental) - https://github.com/europlanet-gmap/sharpy - sharad download and preprocess for 3D visualization
* MARSIS_EDR-RDR_PDS-Downloader - https://github.com/europlanet-gmap/MARSIS_EDR-RDR_PDS-Downloader - Direct downloader of MARSIS EDR/RDR Data from PDS using only orbit number from user input (csv file or interactively)
* MARSIS-xDR-READER - https://github.com/europlanet-gmap/MARSIS-xDR-READER.git - Tool for read MARSIS EDR/RDR/RAW data and convert into different formats (numpy, geopackage, shapefile, png, SEG-Y) and/or ingest into postgresql database
* yutu_radagram_3dmodelling - https://github.com/europlanet-gmap/yutu_radagram_3dmodelling - Tool for create radargrams for 3D visualization of YUTU data
* Open Source access and visualization to public geologic map data:
  * https://github.com/eleanorlutz/mars_geology_atlas_of_space
  * https://github.com/eleanorlutz/moon_geology_atlas_of_space
  * https://github.com/eleanorlutz/topography_atlas_of_space
* planetary-coverage - https://juigitlab.esac.esa.int/python/planetary-coverage - spice-based coverage analysis tool for space missions
* planetmapper - https://github.com/ortk95/planetmapper - visualising, navigating and mapping Solar System observations.

## Planetary geologic mapping tools and aids

* QGIS - https://qgis.org/
* OpenCraterTool - https://github.com/europlanet-gmap/OpenCraterTool
  * https://github.com/thomasheyer/OpenCraterTool
* Circle Craters - https://github.com/sbraden/circle-craters
* CraterStats3 - https://github.com/ggmichael/craterstats
* FGDC Symbology for QGIS - https://github.com/afrigeri/geologic-symbols-qgis
* Mappy (experimental) - https://github.com/europlanet-gmap/mappy - QGIS plugin to ease polygonal maps generation from lines and point

## Tool directories
* PDS Geosciences Node Tools - https://pds-geosciences.wustl.edu/tools/
* PDS tools - https://pds.nasa.gov/tools/about/

## Community support

* OpenPlanetary Forum - https://forum.openplanetary.org/
* ISIS Support - https://github.com/USGS-Astrogeology/ISIS3/issues
* PDS Geosciences Node Community - https://geoweb.rsl.wustl.edu/community/ 

## Planetary geologic mapping - programs and meetings

* USGS Annual Planetary Geologic Mappers meetings - https://planetarymapping.wr.usgs.gov/Page/view/Meetings

## Planetary geologic mapping products

* USGS Maps / Products - https://astrogeology.usgs.gov/maps/
  * e.g. Mercury - https://astrogeology.usgs.gov/search?pmi-target=mercury
  * e.g. Mars - https://astrogeology.usgs.gov/search?pmi-target=mars
* Astrogeology Analysis Ready Data - https://stac.astrogeology.usgs.gov/docs/
* PLANMAP - https://data.planmap.eu

## Training workshops and schools
With offline content/tutorials:

* PDS Data Workshops - https://pds-geosciences.wustl.edu/workshops/default.htm
* ESA Data workshops - https://www.cosmos.esa.int/web/psa/workshops
* PLANMAP / GMAP Winter School 2021 - https://www.europlanet-gmap.eu/planmap-gmap-ws-2021-videos/ - https://www.planetarymapping.eu/391/first-day.html
  * https://forum.openplanetary.org/c/events/Geology-and-Planetary-Mapping-Winter-School-2021/45
* GMAP Winter School 2022 - https://www.europlanet-gmap.eu/planmap-gmap-ws-2022-videos/ - https://www.planetarymapping.eu/401/first-day.html
* GMAP Winter School 2023 - https://www.planetarymapping.eu/413/video-sessions-2023.html - https://indico.obspm.fr/event/1713/contributions/ - https://github.com/europlanet-gmap/winter-school-2023

## Tutorials 
* Short QGIS (v2.x) Tutorial - https://github.com/thareUSGS/QGIS_tutorials
* Tennessee Tech University ArcGIS Pro Tutorials - https://tntechsedgeology.org/tutorials/
* USGS geologic mapping and GIS-related tutorials - [MRCTR GIS Lab](https://www.usgs.gov/special-topics/planetary-geologic-mapping/planetary-mapping-and-gis-tutorials)

## Spectral data and processing
* List of spectral indices - https://github.com/davemlz/awesome-spectral-indices

## Visualization tools and plugins
* Blender GIS - https://github.com/domlysz/BlenderGIS

## Generic Processing tools
* Raster footprint generator and very large raster data processing - https://grasswiki.osgeo.org/wiki/Large_raster_data_processing

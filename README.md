# Global wetland fractional coverage map for the late 20th century

This map was produced around 2003 based on the best available data that
existed at that time. Data from various sources described below were
compiled by Jed O. Kaplan and used in several studies chiefly on
modeling the global methane budget including the publication in which
the map was first described (Bergamaschi et al., 2007). The map was used
to drive a simple model of wetland methane sources (Kaplan, 2002; Kaplan
et al., 2006) and constrain the global wetland methane source. The data
set contains an aggregate global wetland fraction layer, as well as
several other thematic layers that have regional coverage.

The data are stored in a [NetCDF](https://www.unidata.ucar.edu/software/netcdf/) (version 4) files and have the following attributes:

- Spatial extent: Entire Earth
- Spatial reference system (SRS): Unprojected (geographic, WGS84)
- Spatial resolution: 30 arc-minute (0.5 degree)
- Temporal extent: late 20th century
- Temporal resolution: 1 timeslice

Dataset DOI: <https://doi.org/10.5281/zenodo.18274983>

Because of known inconsistencies in available data sets of global
wetland area and the availability of new, high-resolution land cover
maps (including wetland classification) for certain continents, we
compiled an original map of global wetlands. The map was assembled using
the best available source of large-scale wetland cover information for
each continent or region. While several of the data sets contained
subclassifications of wetland type (e.g., bog, fen, forested wetland, or
floodplain), it was not possible to create a globally consistent data
set containing more information than simple presence or absence of
wetland. Some data sets were vector polygon products while others were
raster maps at resolutions from 30 m to 50 (10 km). To create the global
data set, we calculated the fractional cover of wetland area on a global
0.5° geographic grid. We used five major data sources to assemble the
global wetland map. For Canada we used the vector Canadian Peatlands
Database (Tarnocai et al., 2000), rasterizing the map at 1 km resolution
and aggregating fractional wetland cover to a 0.5° grid. For the
conterminous United States, we used the 30 m U.S. National Land Cover
Dataset (Vogelmann et al., 2001). Data for South America, Africa,
Eastern Europe, and northern Asia come from the 1 km native resolution
GLC2000 global land cover data set (Joint Research Centre, 2003). Data
for Europe is from the 250 m CORINE90 Land Cover data set (European
Topic Centre on Terrestrial Environment, 2000). For all other regions we
used the 50 WELAREM1 database of global wetlands (Lehner & Döll, 2001).

**References**

Bergamaschi, P., Frankenberg, C., Meirink, J. F., Krol, M., Dentener,
F., Wagner, T., Platt, U., Kaplan, J. O., Korner, S., Heimann, M.,
Dlugokencky, E. J., & Goede, A. (2007). Satellite chartography of
atmospheric methane from SCIAMACHYon board ENVISAT: 2. Evaluation based
on inverse model simulations. *Journal of Geophysical
Research-Atmospheres, 112*(D2). doi:10.1029/2006jd007268

European Topic Centre on Terrestrial Environment. (2000). *Corine land
cover database (Version 12/2000 extended coverage)*. Retrieved from:
<https://land.copernicus.eu/en/products/corine-land-cover/clc-2000>

Joint Research Centre. (2003). *Global Land Cover 2000*. Retrieved from:
<https://forobs.jrc.ec.europa.eu/glc2000/data>

Kaplan, J. O. (2002). Wetlands at the Last Glacial Maximum: Distribution
and methane emissions. *Geophysical Research Letters, 29*(6).
doi:10.1029/2001gl013366

Kaplan, J. O., Folberth, G., & Hauglustaine, D. A. (2006). Role of
methane and biogenic volatile organic compound sources in late glacial
and Holocene fluctuations of atmospheric methane concentrations. *Global
Biogeochemical Cycles, 20*(2). doi:10.1029/2005gb002590

Lehner, B., & Döll, P. (2001). *The 1' global wetlands, lakes and
reservoirs map WELAREM1*. Retrieved from:
<https://www.uni-frankfurt.de/45218095/WELAREM1>

Tarnocai, C., Kettles, I. M., & Lacelle, B. (2000). Peatlands of Canada.
*Geological Survey of Canada, Open File, 3834*. doi:10.4095/211269

Vogelmann, J. E., Howard, S. M., Yang, L. M., Larson, C. R., Wylie, B.
K., & Van Driel, N. (2001). Completion of the 1990s National Land Cover
Data set for the conterminous United States from Landsat Thematic Mapper
data and Ancillary data sources. *Photogrammetric Engineering and Remote
Sensing, 67*(6), 650-661.

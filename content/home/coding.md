+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 62  # Order that this section will appear.

title = "Data Science"
subtitle = "Making art with Python :ear_of_rice: :computer: :man_farmer:"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  image = "coding.png"  # Name of image in `static/img/`.
  image_darken = 0.85  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  image_position = "center"  # Options include `left`, `center` (default), or `right`.
  image_parallax = true  # Use a fun parallax-like fixed background effect? true/false

  # Text color (true=light or false=dark).
  text_color_light = true

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

## **Operating systems**
Windows, Linux (Ubuntu), Unix.

## **Programming languages**
Python, .NET (medium, [APSIM Classic](https://www.apsim.info/documentation/model-documentation/infrastructure-and-management-documentation/manager-2/), 
[APSIM Next Generation](https://apsimnextgeneration.netlify.app/usage/writemanagerscript/)), C#, Markdown (advanced), R Studio, Shell.

## **Data analysis and exploration**
Python (pandas, statsmodels, sqlite3, json, glob, os, functools, lxml [handling of XML and HTML files], csv).

## **Machine learning, optimization, linear algebra and statistics**
Python (numpy, scipy, scikit-learn [e.g. KMeans used for data clustering], pandas, matplotlib, math).

## **Data visualization and mapping**
Python (seaborn, dask, xarray, cartopy, pyproj, shapefile, netCDF4, geopandas, rasterio, GDAL), remote sensing imagery in vegetation and soil moisture 
mapping (MODIS, Sentinel2, Sentinel1-SAR), ArcGIS, QGis, netCDF file format, and relational databases. pSIMS (gridded crop model simulations), [nco operators](http://nco.sourceforge.net/) (manipulates 
and analyzes data stored in netCDF in Linux), [FluroSense](https://www.regrow.ag/flurosense) (Regrow Ag cloud-based crop management and analytics platform that drives planting and growing decisions).

## **Cloud computing, parallel computing and storage**
Google Cloud Platform, Docker, [Singularity](https://singularity.hpcng.org/), Amazon Web Services, GitHub repositories, APIs, Swift, SQL tools (Database Client, 
SQL editor, Visual Query Builder, e.g. DBeaver).

## **Software development and collaboration tools**
Bestiapop (Python package to automate the extraction and processing of climate data for crop modelling, >3000 downloads), [Atlassian](https://www.atlassian.com/) 
(Jira and Confluence), [Buddy](https://buddy.works/) (The DevOps Automation Platform), GitHub operations, Jupyter Notebook/Lab, Spyder, Anaconda, PostMan, Visual Studio.

## **Mechanistic models and decision support tools**
[APSIM Next Generation](https://apsimnextgeneration.netlify.app/),
[APSIM Classic](https://www.apsim.info/),
[DSSAT](https://dssat.net/),
[SIMPLACE](http://www.simplace.net/),
[MONICA](https://soil-modeling.org/resources-links/model-portal/monica),
[CropWat](http://www.fao.org/land-water/databases-and-software/cropwat/es/),
[pSIMS](https://github.com/JJguri/psimsV2),
[DNDC](https://www.dndc.sr.unh.edu/)
 
## **Tools development for automated data processing**

## [**pSIMSv2**](https://github.com/JJguri/psimsV2)

#### _Developers_
- Jonathan Ojeda (QAAFI, The University of Queensland)
- Pete deVoil (QAAFI, The University of Queensland)

#### _Collaborators_
- Isaiah Huber (Iowa State University)
- Chris James (School of Agriculture and Food Sciences, The University of Queensland)
- Diego Perez (Data Analytics Specialist & Cyber Security Expert)

#### _Overview_
The original Parallel System for Integrating Impact Models and Sectors (pSIMS) was developed by 
[Elliot et al. (2014)](https://www.sciencedirect.com/science/article/pii/S1364815214001121?casa_token=Tiz73PnBf9MAAAAA:cj6f6VItLQGgBMEY5VMyYjHT3a4QtpNcUYkAE-MY8HloVcyKidUtEOo_ntMV2Ft_dkCC2epi-xI) in 
Python 2, we updated pSIMS to pSIMSV2 which is able to run the APSIM sorghum module at a regional scale (US-wide) using netCDF input data (climate, soil and crop management).
pSIMSV2 has the ability to run APSIM using a singularity image which avoid the need to install the soft dependencies manually.

## [**MappingTools**](https://github.com/JJguri/Mapping-tools)

#### _Developer_
- Jonathan Ojeda (QAAFI, The University of Queensland)

#### _Overview_
Visualisation tools to map crop features and environmental variables across regions. Main functionalities include: import shp and tif files, use Basemap, edit legend and work with iso_3 codes, plot categories by country,
edit legends in the map, inset charts in the map, read netCDF using xarray, explore and plot multidimensional 
files using xarray, create maps using xarray and dataframes, create 2D dataframe from xarray, create 
multi-dimensional xarray from 2D pandas dataframe, work with NASS API for crop statistics, etc...

## [**RemoteSensingApplications**](https://github.com/JJguri/RemoteSensingCropModels)

#### _Developer_
- Jonathan Ojeda (QAAFI, The University of Queensland)

#### _Overview_
Tools to use remote sensing data (MODIS, Sentinel2, NASA-POWER, etc) to validate crop models. These include
the data curation and data analysis of remote sensing products before being used to validate models. Examples
for linking APSIM Classic and Next Generation outputs with RS products are included.

## [**VarianceDecomposition**](https://github.com/JJguri/VarianceDecomposition)

#### _Developers_
- Jonathan Ojeda (QAAFI, The University of Queensland)
- Bahareh Kamali (University of Bonn)

#### _Overview_
This tool allows calculating the variance contribution of several factors on different crop model outputs. The
theory developed by [Monod 2006](https://reseau-mexico.fr/sites/reseau-mexico.fr/files/06_zebook_CH-03.pdf) was
converted to a single Jupyter Notebook through Python. This tool produces a series of plots that allow the user to see the weight
of each factor on the variance of crop yield.

## [**WebsiteBuilder**](https://github.com/JJguri/cv)

#### _Developer_
- Jonathan Ojeda (QAAFI, The University of Queensland)

#### _Overview_
During my free time, I enjoy writing my own webpage (the page you are reading right now!) in Markdown using the Hugo platform.
Hugo is a popular static site generator written in the Go programming language. Hugo is jam-packed with features, 
but one of its main selling points is speed — Hugo takes mere seconds to generate a site with thousands of pages.
By default, Hugo uses the Goldmark Markdown processor which is fully CommonMark-compliant.

+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Coding"
subtitle = "Model development, programming and coding skills, git operations"

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

## [**Bestiapop**](https://pypi.org/project/bestiapop/)

#### _Developers_
- Jonathan Ojeda (QAAFI, The University of Queensland)
- Diego Perez (Data Analytics Specialist & Cyber Security Expert)

#### _Overview_
BestiaPop (a spanish word that translates to pop beast), is a Python package which allows climate and agricultural data scientists 
to automatically download SILO’s (Scientific Information for Land Owners) or NASAPOWER gridded climate data and convert this data to 
files that can be ingested by Crop Modelling Software like APSIM or DSSAT. The package offers the possibility to select a range of grids 
(5 km × 5 km resolution) and years producing various types of output files: CSV, MET (for APSIM), WTH (for DSSAT) and soon JSON (which will 
become part of BestiaPop’s API in the future).

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
[Elliot et al. (2014)](https://www.sciencedirect.com/science/article/pii/S1364815214001121?casa_token=Tiz73PnBf9MAAAAA:cj6f6VItLQGgBMEY5VMyYjHT3a4QtpNcUYkAE-MY8HloVcyKidUtEOo_ntMV2Ft_dkCC2epi-xI) in Python 2, we updated pSIMS to pSIMSV2 which is able to run in a Python 3 environment. 
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

## [**APSIMClassicTools**](https://github.com/JJguri/APSIMClassicTools)
## [**APSIMNextGenTools**](https://github.com/JJguri/APSIMNextGenTools)

#### _Developer_
- Jonathan Ojeda (QAAFI, The University of Queensland)

#### _Overview_
Series of tools that allow users to interact between two APSIM versions 
(Classic and Next Generation) and Python through Jupyter Notebook. Main functionalities include: read **_.out_** files
and **_.db_** files, create new variables, clean model outputs, create time series plots and XY plots, etc.

---
title: bestiapop - A python package for climate data extraction and processing

summary: 2019-2020
tags:
- Weather data
- Model inputs
- APSIM modelling
- MET file
- Python
- APSIM Next Generation
- APSIM Classic
date: "2018-06-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by https://www.longpaddock.qld.gov.au/silo/
  focal_point: Smart

links:
- icon: linkedin
  icon_pack: fab
  name: Follow
  url: https://www.linkedin.com/in/jonathan-j-ojeda-09147047/
- icon: github
  icon_pack: fab
  name:
  url: https://github.com/JJguri/bestiapop
url_code: ""
url_pdf: "https://www.dropbox.com/s/00mcy5onulnpnnr/paper_silo.pdf?dl=0"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

![PyPI - Downloads](https://img.shields.io/pypi/dm/bestiapop?style=flat-square)

Climate data is an essential input for crop models to predict crop growth and development using site-specific (point) or gridded climate data. While *point* data is currently available in MET format, *gridded data* is provided in NetCDF file format which is difficult to store and convert to an input file readable by [APSIM](https://www.apsim.info) or other crop models. We developed **bestiapop** (a spanish word that translates to *pop beast*), a Python script (*soon to become a package*) which allows model users to automatically download gridded climate data, e.g. SILO's (Scientific Information for Land Owners) data in a crop model format such as MET file format in APSIM or WHT format in [DSSAT](https://dssat.net/) that can then be inputted for **crop modelling predictions**. The package offers the possibility to select a range of grids (5 km × 5 km resolution) and years producing various types of output files: MET, WHT and soon csv, SQLite and Jason.

Although the code currently downloads data from the [SILO](https://www.longpaddock.qld.gov.au/silo/gridded-data/) database, it will be updated to be applied to other climate data sources e.g. [NASA POWER](https://power.larc.nasa.gov/) as was impplemented in R using [APSIM CRAN](https://cran.r-project.org/web/packages/APSIM/APSIM.pdf).

### Authors

**Data Analytics Specialist & Code Developer**: Diego Perez [@darkquassar](https://github.com/darkquasar)

**Data Scientist, Crop Physiologist & Crop Modeller**: Jonathan Ojeda [@JJguri](https://github.com/JJguri)

### Description

**What is [APSIM](https://www.apsim.info)?**

The Agricultural Production Systems sIMulator (APSIM) is internationally recognised as a highly advanced platform for modelling and simulation of agricultural systems. It contains a suite of modules that enable the simulation of systems for a diverse range of crop, animal, soil, climate and management interactions. APSIM is undergoing continual development, with new capability added to regular releases of official versions. Its development and maintenance is underpinned by rigorous science and software engineering standards. The [APSIM Initiative](https://www.apsim.info/about-us/) has been established to promote the development and use of the science modules and infrastructure software of APSIM.

**What is a MET file?**

The APSIM Met module provided daily meteorological information to all modules within an APSIM simulation. The APSIM Met Module requires parameters to specify the climate of the site for each APSIM time step. This information is included in a [MET file](https://www.apsim.info/documentation/model-documentation/infrastructure-and-management-documentation/met/).

APSIM MET files consist of a section name, which is always *weather.met.weather*, several constants consisting of *name = value*, followed by a headings line, a units line and then the data. Spacing in the file is not relevant. Comments can be inserted using the ! character.

At a minimum three constants must be included in the file: **latitude**, **tav** and **amp**. The last two of these refer to the annual average ambient temperature and annual amplitude in mean monthly temperature. Full details about tav and amp can be found here: [tav_amp](https://www.apsim.info/wp-content/uploads/2019/10/tav_amp-1.pdf).

The MET file must also have a year and day column (or date formatted as *yyyy/mm/dd*), solar radiation (*MJ/m2*), maximum temperature (*&deg;C*), minimum temperature (*&deg;C*) and rainfall (*mm*). The column headings to use for these are year and day (or date), radn, maxt, mint, rain. Other constants or columns can be added to the file. These then become available to APSIM as variables that can be reported or used in manager script.

**Can I use this script to generate climate files for other process-based crop models?**

So far, the code is producing CSV or MET files to be directly used by APSIM, however, it also could be applied to produce input climate data for other crop models such as [DSSAT](https://dssat.net/) and [STICS](https://www6.paca.inrae.fr/stics_eng/About-us/Stics-model-overview). Decision Support System for Agrotechnology Transfer (DSSAT) is a software application program that comprises dynamic crop growth simulation models for over 40 crops. DSSAT is supported by a range of utilities and apps for weather, soil, genetic, crop management, and observational experimental data, and includes example data sets for all crop models. The STICS (Simulateur mulTIdisciplinaire pour les Cultures Standard, or multidisciplinary simulator for standard crops) model is a dynamic, generic and robust model aiming to simulate the soil-crop-atmosphere system.

### Read code documentation at:

[Script documentation](https://bestiapop.readthedocs.io/en/latest/?badge=latest)

[GitHub repo](https://github.com/JJguri/bestiapop)

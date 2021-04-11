---
title: Bestiapop - A python package for climate data extraction, processing and visualisation in crop models

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

<img src="https://img.shields.io/pypi/dm/bestiapop?style=flat-square" width="1000"/>

Climate data is an essential input for crop models to predict crop growth and development 
using site-specific (point) or gridded climate data. While *point* data is currently available 
in MET format, *gridded data* is provided in NetCDF file format which is difficult to store and 
convert to an input file readable by [APSIM](https://www.apsim.info) or other crop models. 
We developed **bestiapop** (a spanish word that translates to *pop beast*), a Python package 
which allows model users to automatically download thousand files of gridded climate 
data from two data sources [SILO](https://www.longpaddock.qld.gov.au/silo/gridded-data/) and 
[NASAPOWER](https://power.larc.nasa.gov/) in a crop model format such as 
MET format in APSIM or WHT format in [DSSAT](https://dssat.net/) that can then be inputted 
for **crop modelling predictions**. The package offers the possibility to select a range of grids 
(5 km × 5 km resolution) and years producing various types of output files: MET, WHT and CSV and soon 
SQLite and Jason. Users can also visualise data statistics (mean, standard deviation, CV, etc) spatially 
for any selected region in the world.

### Authors

**Data Analytics Specialist & Code Developer**: Diego Perez [@darkquassar](https://github.com/darkquasar)

**Data Scientist, Crop Physiologist & Crop Modeller**: Jonathan Ojeda [@JJguri](https://github.com/JJguri)

### Use it in Jupyter Notebook
If you would like to use BESTIAPOP in you Jupyter Notebook, you can! Please see the [example notebook](https://github.com/JJguri/bestiapop/blob/master/sample-data/ExampleMapsTasmania.ipynb).
You can also try it live in Binder Project, just hit the badge mate! --> [BestiapopBinder](https://mybinder.org/v2/gh/JJguri/bestiapop/HEAD?filepath=sample-data%2FExampleMapsTasmania.ipynb)
If you download files, you can retrieve them via the Jupyter interface :)

### Data visualisation product from Bestiapop
![image](/img/projects/tassie.png)

_The 5 km grids in the figure represents the yearly mean [across 132 years (1889-2020)] of 
the mean maximum temperature retrieved from SILO_

### Read code documentation at:

[Documentation](https://bestiapop.readthedocs.io/en/latest/?badge=latest)

[GitHub repo](https://github.com/JJguri/bestiapop)

[Pypi](https://pypi.org/project/bestiapop/)

### References
1. Ojeda JJ, Eyshi Rezaei E, Remenyi TA, Webber HA, Siebert S, Meinke H, Webb MA, Kamali B, Harris RMB, Kidd DB, Mohammed CL, McPhee J, Capuano J, Ewert F (2021) Implications of data aggregation method on crop model outputs – The case of irrigated potato systems in Tasmania, Australia. 
European Journal of Agronomy.126, 126276. [link](doi.org/10.1016/j.eja.2021.126276)

2. Ojeda JJ, Eyshi Rezaei E, Remenyi TA, Webb MA, Webber HA, Kamali B, Harris RMB, Brown JN, Kidd DB, Mohammed CL, Siebert S, Ewert F, Meinke H (2020) Effects of soil- and climate data aggregation on simulated potato yield and irrigation water requirement. 
Science of the Total Environment. 710, 135589. [link](doi:10.1016/j.scitotenv.2019.135589)

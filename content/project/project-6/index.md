---
title: The BestiaPop - A Python package to automatically generate gridded climate data for crop models

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

Climate data is an essential input for crop models to predict crop growth and development using site-specific (point) or gridded climate data. While point data is currently available in a readily APSIM format, gridded data is storage in NetCDF files which are difficult to storage and convert to an input file readable by APSIM or other crop models. We developed BestiaPop, a Python package which allows model users to automatically download SILO's (Scientific Information for Land Owners) gridded climate data in an APSIM format. The package offers the possibility to select a range of grids (5 km × 5 km resolution) and years producing a file with climate data available at SILO. The package was tested across areas suitable for potato (Solanum tuberosum L.) in Tasmania, Australia. A total of 1731 climate files across 20 years (1998-2017) were automatically downloaded and the spatio-temporal variability of climate inputs was mapped. The case study reveals that the implemented BestiaPop is a useful and efficient tool to automatically download gridded climate data in an APSIM format and could be extended to other crop models and regions across Australia.

#### Parterns
Diego Perez @darkquasar (Hydro Tasmania)
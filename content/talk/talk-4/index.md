---
slug: "bestia-pop"
title: BestiaPop - A Python package to automatically generate and visualise gridded climate data for crop model applications (oral presentation)
event: Australian Agronomy Conference
event_url: https://expertevents.eventsair.com/QuickEventWebsitePortal/australian-agronomy-conference/finalprogram

location: Toowoomba Australia
address:
  street: 54-56 Neil St
  city: Toowoomba
  region: Australia
  postcode: '4350'
  country: Australia

summary: Bestiapop functionality and applications
abstract: "Climate data is an essential input for crop models to predict crop growth and development using site-specific (point) or gridded climate data. While point data is usually available in a readily format, gridded data is stored in NetCDF files which are difficult to archived and convert to an input file readable by the Agricultural Production Systems sIMulator (APSIM) or other crop models such as the Decision Support System for Agrotechnology Transfer (DSSAT). We developed BestiaPop, a Python package which allows model users to automatically download gridded climate data in an APSIM and DSSAT format from an Australian (Scientific Information for Land Owners; SILO) and global (NASA- Prediction Of Worldwide Energy Resource; NASA-POWER) climate data source. The package offers the possibility to select a range of grids (0.05° resolution) and years producing files with daily climate data in different formats (CSV, MET, WTH). We (i) compared the Bestiapop performance to download CSV, MET and WTH files using multiprocessing and (ii) tested the performance of the package to generates climate data across areas suitable for potato (Solanum tuberosum L.) in Tasmania, Australia. A total of 1724 climate files across 20 years (1991-2020) were automatically downloaded and the spatio-temporal variability of climate inputs was mapped. The case study reveals that implementing BestiaPop is a useful and efficient tool to automatically download gridded climate data in an APSIM format and could be extended to other crop models and regions across the world."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2022-09-20T16:15:00Z"
date_end: "2022-09-20T16:25:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2022-11-17T00:00:00Z"

authors: [Ojeda JJ, Perez D]
tags: [Gridded climate data, Crop models, Regional analysis]

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point: Right

url_code: ""
url_pdf: ""
url_slides: "https://www.dropbox.com/s/whqwxie17fz1368/ASA_Ojeda_J_002_bestiapop.pptx?dl=0"
url_video: "https://www.dropbox.com/s/gh4yytqg2lmebp8/bestiapop.mp4?dl=0"

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
- internal-project

# Enable math on this page?
math: true
---

+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 61  # Order that this section will appear.

title = "Bestiapop"
subtitle = "A python package to automate the extraction, processing and visualisation of climate data for crop modelling"

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
  image = "bestiapop.jfif"  # Name of image in `static/img/`.
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

#### _Developers_
- Jonathan Ojeda (QAAFI, The University of Queensland)
- Diego Perez (Data Analytics Specialist & Cyber Security Expert)

<img src="https://img.shields.io/pypi/pyversions/bestiapop?style=flat-square" width="200" />

<img src="https://static.pepy.tech/badge/bestiapop" width="200" />

<img src="https://img.shields.io/pypi/dm/bestiapop?style=flat-square" width="500"/>

#### _Overview_
Bestiapop (a spanish word that translates to pop beast), is a Python package which allows climate and agricultural data scientists 
to automatically download SILO’s (Scientific Information for Land Owners) or NASAPOWER gridded climate data and convert this data to 
files that can be ingested by Crop Modelling Software like APSIM or DSSAT. The package offers the possibility to select a range of grids 
(0.05° x 0.05° for SILO and 0.5° x 0.5° for NASAPOWER) and years producing various types of output 
files: CSV, MET (for APSIM), WTH (for DSSAT) and soon JSON (which will 
become part of Bestiapop’s API in the future). Users can also visualise data statistics (mean, standard deviation, CV, etc) spatially 
for any selected region in the world.

If you would like to use Bestiapop in Jupyter Notebook, you can [see here](https://github.com/JJguri/bestiapop/blob/master/sample-data/ExampleMapsTasmania.ipynb)!
You can also try it live in [Binder Project](https://mybinder.org/v2/gh/JJguri/bestiapop/HEAD?filepath=sample-data%2FExampleMapsTasmania.ipynb) without the need
to install any software in your computer (Yes! :smile: you do not need to know about Python, Anaconda, etc. to use this tool).

#### _Links_

###### [Read more about this project](/modelling/project-6)
###### [Pypi](https://pypi.org/project/bestiapop/)
###### [GitHub](https://github.com/JJguri/bestiapop)
###### [readthedocs](https://bestiapop.readthedocs.io/en/latest/?badge=latest&flat-square)

+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 63  # Order that this section will appear.

title = "APSIM Applications"
subtitle = "Series of tools to develop and test APSIM using Python and C# :nerd_face:"

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
  image = "apsim.png"  # Name of image in `static/img/`.
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

## [**APSIMClassicTools**](https://github.com/JJguri/APSIMClassicTools) & [**APSIMNextGenTools**](https://github.com/JJguri/APSIMNextGenTools)

#### _Developer_
- Jonathan Ojeda (QAAFI, The University of Queensland)

#### _Overview_
Series of tools that allow users to interact between two APSIM versions 
(Classic and Next Generation) and Python through Jupyter Notebook. Main functionalities include: read **_.out_** files
and **_.db_** files, create new variables, clean model outputs, create time series plots and XY plots, etc.

## [**Data visualization for input model configuration**](https://github.com/JJguri/APSIMNextGenTools/blob/main/PaperPotato.ipynb)

#### _Developers_
- Jonathan Ojeda (QAAFI, The University of Queensland)
- Hamish Brown (Plant & Food Research, New Zealand)

#### _Overview_
Crop models are usually developed using a test set of data and simulations representing a 
range of environment, soil, management and genotype combinations. Previous studies demonstrated 
that errors in the configuration of test simulations and aggregation of observed data sets are 
common and can cause major problems for model development. However, the extent and effect of such 
errors are not usually considered as a source of model uncertainty. This code presents a systematic 
method for testing simulation configuration using extensive visualisation approaches. A crop model – 
potato (_Solanum tuberosum_ L.) is described to demonstrate the main 
sources of uncertainty from simulation configuration and data collation. A test set of 426 experiments 
conducted from 1970 to 2019 in 19 countries were run using the APSIM Next Generation model. Plots were made comparing 
simulation configuration across the entire test set . This identified a surprising number of errors and 
inappropriate assumptions that had been made which were influencing model predictions. The approach 
presented here moved the bulk of the effort from fitting model processes to setting up broad simulation 
configuration testing and detailed interrogation to identify current gaps for further model development.

## [**APSIM Classic Miscanthus**](https://github.com/APSIMInitiative/APSIMClassic/tree/master/Examples/BioEnergy) &
## [**APSIM Classic Switchgrass**](https://github.com/APSIMInitiative/APSIMClassic/tree/master/Examples/BioEnergy)

#### _Developer_
- Jonathan Ojeda (as Fulbright scholar at Purdue University)

#### _Overview_

APSIM Classic was modified so that it could accurately predict growth and yield of switchgrass and Miscanthus; 
two plant species that were not represented in this large, multi-species model. Two existing APSIM sub-models 
(lucerne, sugarcane) were altered using knowledge of species-specific differences in growth, development and agronomic practices. 
Large databases for soils and weather were assembled for subsequently association with site-specific yield data of 
both species and successfully calibration and validation. These NEW APSIM sub-models predict 
the yield of both species across broad geographies from the East Coast to the Great Plains of the US.

#### [Read the paper in Global Change Biology Bionenergy here](https://onlinelibrary.wiley.com/doi/full/10.1111/gcbb.12384)


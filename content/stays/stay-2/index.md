---
slug: "purdue"
title: Purdue University
summary: 2015 - Visiting Researcher
tags:
- Crop modelling
- Bioenergy crops
- Corn-Soybean
- Water drainage
- APSIM Classic
date: "2015-05-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

links:
- icon: cow
  icon_pack: far
  name: Purdue
  url: https://www.purdue.edu/
- icon: cow
  icon_pack: far
  name: WQFS
  url: https://ag.purdue.edu/agry/WQFS/Pages/default.aspx

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

### Department of Agronomy, Purdue University, West Lafayette, Indiana, US

#### Period
From May 2015 to Mar 2016

#### Activities

1. I modified APSIM Classic so that it could accurately predict growth and yield of switchgrass and Miscanthus; two plant species that are not yet represented in this large, multi-species model. I altered two existing APSIM sub-models (lucerne, sugarcane) using knowledge of species-specific differences in growth, development and agronomic practices. In brief the modifications for Miscanthus include radiation use efficiency and biomass partitioning. The modifications for Switchgrass were more extensive and included the thermal time calculation, biomass partitioning, radiation use efficiency, transpiration efficiency, temperature dependency of photosynthesis and the light extinction coefficient. I also assembled large databases for soils and weather that I could subsequently associate with site-specific yield data of both species and successfully calibrated and validated both of these new sub-models. These new APSIM sub-models predict yield of both species across broad geographies from the East Coast to the Great Plains of the US.

2. I altered the APSIM maize model routine in substantive ways to predict corn yield in continuous corn and soybean-corn rotations. First, I successfully calibrated and validated the model using data from the Eastern cornbelt of the US. I then used water flow and agronomic data from Purdue’s Water Quality Field Station (WQFS) to calibrate the water use/drainage sub-routine of water balance data can be obtained. This enabled to make improvement in the APSIM maize model not otherwise possible.

#### Achievements

**_Publications_**

1. _Ojeda JJ, Volenec JJ, Brouder SM, Caviglia OP, Agnusdei MG (2017) Evaluation of Agricultural Production Systems Simulator (APSIM) as yield predictor of Panicum virgatum and Miscanthus x giganteus in several US environments. Global Change Biology Bioenergy. 9, 796-816. doi:10.1111/gcbb.12384_

2. _Ojeda JJ, Volenec JJ, Brouder SM, Caviglia OP, Agnusdei MG (2018) Modelling stover and grain yields, and subsurface artificial drainage from long-term corn rotations using APSIM. Agricultural Water Management. 195, 154-171. doi:10.1016/j.agwat.2017.10.010_

**_Model development_**

_Adaption of APSIM Sugar and Lucerne to represent Miscanthus and Switchgrass_

This code contains simulations of Sugar adapted to represent Miscanthus and Lucerne to represent Switchgrass.

https://github.com/APSIMInitiative/APSIMClassic/tree/master/Examples/BioEnergy

#### Host Researchers
* Dr Jeffrey Volenec and Dr Sylvie Brouder (Purdue University)

#### Funded by
Fulbright Fellowship, Fulbright Commission, United States

#### Grant amount
AUD $37,000



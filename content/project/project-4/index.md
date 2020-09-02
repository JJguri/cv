---
title: APSIM Potato model development - Mapping potato yield variability under diferent G*E*M scenarios in Tasmania 
summary: 2018-2021
tags:
- APSIM Next Generation
- Crop model development
- Model configuration
- Farm data
- APSIM Next Generation
- Simplot
- McCain
- Scenario analysis
date: "2018-11-07T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by https://www.foodandbeveragetasmania.com/
  focal_point: Smart

links:
- icon: cow
  icon_pack: fab
  name: Read UTAS Article about the project
  url: https://www.utas.edu.au/alumni/news-and-publications/news-items/sowing-the-seeds-of-success-for-the-humble-spud
- icon: cow
  icon_pack: fab
  name: Listen to ABC Country Hour interview at 15:10 mins
  url: https://www.abc.net.au/radio/programs/tas-country-hour/tasmanian-country-hour/12561548
- icon: cow
  icon_pack: fab
  name: Twitter Post
  url: https://twitter.com/TasInAg/status/1299120759973924864?s=20
- icon: cow
  icon_pack: fab
  name: TasCountry article
  url: https://www.dropbox.com/s/eywlzch0f4lm2eg/TasCountry.pdf?dl=0

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

Potato farmers often need to face up with complex interactions (genotype [G] * management [M] * environment [E]), which are difficult and costly to diagnose and ameliorate. The specific nature of such interactions and the significant cost to address improvement decisions is an ideal use case for DSS. On the other hand, there were limited modeling studies based on combined analysis of genotype [G] * management [M] * environment [E], which are key to assessing tuber yield variability (spatial and temporal). This project is developing an improved and complete version of the released APSIM Potato model based on a G*M*E approach. This model would be a first step towards the development of several APSIM sub-models to simulate tuber yield for different potato genotypes under different crop management strategies. The model should be able to describe in a mechanistic way the processes that have been previously identified as the key determinant of water use, total dry biomass production, and tuber production (e.g. number stems per tuber, phenology, genotypic parameters, etc.).

The project has three main research branches:

- Developing a methodological approach for assessing errors during simulation configuration using Python
- Model developing using a test set of 426 experiments conducted from 1970 to 2019 in 19 countries (55 locations) including 44 cultivars.
- Model testing using real farm data across Tasmania (Simplot and McCain farms)
- Developing visualisation tools to assess the spatio-temporal variability of crop yield.

This project will develop a new visualisation tool to assess the spatio-temporal variability of predicted potato yields and water use under climate change scenarios in Tasmania. The main hypothesis is that yield, and water use differs with the spatial and temporal scale under contrasting climate change scenarios (drought and heat stress). We will address two key questions:

1)	Which climatic and crop management factors are dominant in explaining irrigated potato yield variability at the regional scale? 
2)	How do the drivers of potato yield variability change with irrigation strategies, sowing dates, and cultivars chosen under different climatic extremes?

The project will pioneer the regional modelling of potato yield as a case study at different spatial scales, information required to assess ongoing agricultural intensification through irrigation schemes (aligned with AgriVision-2050 for Tasmania). A crop model will be calibrated using environmental gridded data and farm data, and then future climate scenarios will be applied based on current irrigation management data provided by Simplot/McCain farmers. The main output of the project will be a visualisation tool (maps) that will allow end-users, particularly potato growers to visualize the current and future spatio-temporal variability of yield and water use across potato growing regions in Tasmania.

One of the first milestones achieved for this project was the development of crop yield variability maps across the entire potato production areas of Tasmania. These maps will be hosted in the [LISTmap](https://maps.thelist.tas.gov.au/listmap/app/list/map) website for free access online. Below is an example of crop yield variability for different soils and irrigation strategies.

![image](/img/projects/maps.jpg)
_Figure caption. Simulated yield (30 year means; 1960-1990) for early-planting date (5th October) for each soil type (BrC, Brown Chromosol; ReD, Red Dermosol; BrK, Brown Kurosol; GrK, Grey Kurosol; BrF, Brown Ferrosol; ReF, Red Ferrosol; BlC, Black Chromosol; BrD, Brown Dermosol) and irrigation strategy (OPT - Optimum; HIGH - High; MED - Medium; LOW - Low) in the potato production region in Tasmania. Values inside parenthesis after the name of soil type indicate the maximum plant available water capacity (mm). Means (t ha-1) and coefficient of variation (%) (in parenthesis) of simulated yield across years and grid cells are shown at the top of each map. White grids indicate non-agricultural areas._

#### Partners
Plant and Food Research New Zealand (Dr Hamish Brown), CSIRO (Dr Neil Huth, Dean Holzworth), Tasmanian Institute of Agriculture (John McPhee) Simplot Tasmania (Frank Mulcahy, Ed Blanchard), McCain Tasmania (Rodney Smith).

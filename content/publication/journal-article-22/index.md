---
slug: "apsim-model-outputs"
title: "Investigating the effects of APSIM model configuration on model outputs across different environments"

authors:
- Chapagain R
- Remenyi TA
- Huth N
- Mohammed CL
- Ojeda JJ

date: "2023-07-30T00:00:00Z"
doi: "https://doi.org/10.3389/fpls.2023.1206535"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-07-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
# publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Frontiers in Plant Science"
publication_short: ""

abstract: 

Introduction: Soil type plays a major role in nutrient dynamics and soil water which impacts crop growth and yield. The influence of soil characteristics on crop growth is usually evaluated through field experimentation (in the short term) and through crop-soil modelling (in the long-term). However, there has been limited research which has looked at the effect of model structural uncertainty of model outputs in different soil types.
Methods: To analyze the impact of soil inputs on model structural uncertainty, we developed eight model structures (a combination of two crop models, two soil water models and two irrigation models) within the Agricultural Production Systems sIMulator (APSIM) across three soil types (Ferralsols, Alisols and Chernozems). By decomposing the mean proportion of variance and simulated values of the model outputs (yield, irrigation, drainage, nitrogen leaching and partial gross margin) we identified the influence of soil type on the magnitude of model structural uncertainty.
Results: For all soil types, crop model was the most significant source of structural uncertainty, contributing >60% to variability for most modelled variables, except irrigation demand which was dominated by the choice of irrigation model applied. Relative to first order interactions, there were minimal (<12%) contributions to uncertainty from the second order interactions (i.e., inter-model components). We found that a higher mean proportion of variance does not necessarily imply a high magnitude of uncertainty in actual values. Despite the significant impact of the choice of crop model on yield and PGM variance (contributing over 90%), the small standard deviations in simulated yield (ranging from 0.2 to 1 t ha-1) and PGM (ranging from 50.6 to 374.4 USD ha-1) compared to the mean values (yield: 14.6 t ha-1, PGM: 4901 USD ha-1) indicate relatively low actual uncertainty in the values. Similarly, the choice of irrigation model had a contribution of over 45% to variance, but the relatively small standard deviations ranging from 11 to 33.3 mm compared to the overall mean irrigation of 500 mm suggest low actual uncertainty in the values. In contrast, for the environmental variables- drainage and nitrogen leaching, the choice of crop model had contributions of more than 60% and 70% respectively, yet the relatively large standard deviations ranging from 7.1 to 30.6 mm and 0.6 to 7.7 kg ha-1 respectively, compared to the overall mean values of drainage (44.4 mm) and nitrogen leaching (3.2 kg ha-1), indicate significant actual uncertainty.
Discussion: We identified the need to include not only fractional variance of model uncertainty, but also magnitude of the contribution in measured units (e.g. t ha-1, mm, kg ha-1, USD ha-1) for crop model uncertainty assessments to provide more useful agronomic or policy decision-making information. The findings of this study highlight the sensitivity of agricultural models to the impacts of moisture availability, suggesting that it is important to give more attention to structural uncertainty when modelling dry/wet conditions depending on the output analyzed.

# Summary. An optional shortened abstract.
summary: We analyzed the effects of model structural uncertainty on model outputs across soil types.

tags:
- APSIM
- Soil Texture
- Soil Type
- Organic Carbon
- Spatial Heterogeneity
- Rainfall Environment
- Climate

featured: true

url_pdf: 'https://www.dropbox.com/scl/fi/nl9i8xs4j8zmbpxv1gwyj/23.-Chapagain-et-al.-2023-FPS.pdf?rlkey=kmr4h73b0idh4iw4y5y4fsrix&st=xadkbc8a&dl=0'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

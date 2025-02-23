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
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Frontiers in Plant Science"
publication_short: ""

abstract: |
  **Introduction:**  
  Soil type plays a major role in nutrient dynamics and soil water, impacting crop growth and yield. 
  The influence of soil characteristics on crop growth is usually evaluated through field experimentation 
  (short-term) and crop-soil modeling (long-term). However, limited research has examined the effect of 
  model structural uncertainty in different soil types.

  **Methods:**  
  To analyze the impact of soil inputs on model structural uncertainty, we developed eight model structures 
  (a combination of two crop models, two soil water models, and two irrigation models) within the Agricultural 
  Production Systems sIMulator (APSIM). These were tested across three soil types: Ferralsols, Alisols, and Chernozems. 
  By decomposing the mean proportion of variance and simulated values of the model outputs (yield, irrigation, 
  drainage, nitrogen leaching, and partial gross margin), we identified the influence of soil type on model 
  structural uncertainty.

  **Results:**  
  - For all soil types, the **crop model** was the most significant source of structural uncertainty (>60% variability).
  - **Irrigation demand** was dominated by the choice of the irrigation model.
  - Second-order interactions between model components contributed **<12%** to overall uncertainty.
  - High fractional variance did not necessarily indicate high magnitude of uncertainty in actual values.
  - Environmental factors such as drainage and nitrogen leaching showed significant uncertainty due to crop model choice.

  **Discussion:**  
  We highlight the importance of including both **fractional variance and absolute magnitude of uncertainty** (e.g., t ha⁻¹, mm, kg ha⁻¹, USD ha⁻¹) 
  in crop model uncertainty assessments. The findings suggest greater attention is needed for **structural uncertainty** 
  when modeling dry or wet conditions. 

# Summary. An optional shortened abstract.
summary: "We analyzed the effects of model structural uncertainty on model outputs across soil types."

tags:
  - APSIM
  - Soil Texture
  - Soil Type
  - Organic Carbon
  - Spatial Heterogeneity
  - Rainfall Environment
  - Climate

featured: true

url_pdf: "https://www.dropbox.com/scl/fi/nl9i8xs4j8zmbpxv1gwyj/23.-Chapagain-et-al.-2023-FPS.pdf?rlkey=kmr4h73b0idh4iw4y5y4fsrix&st=xadkbc8a&dl=0"
url_code: ""
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
projects: []

# Slides (optional).
slides: "example"
---

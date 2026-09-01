---
title: 'Soil texture prediction with Bayesian generalized additive models for spatial compositional data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Joaquín Martínez-Minaya
  - admin
  - Dae-Jin Lee

# Author notes (optional)
# author_notes:


date: '2026-08-23T00:00:00Z'
doi: 'https://doi.org/10.1007/s00477-026-03339-3'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Stochastic Environmental Research and Risk Assessment*
publication_short: In *Stochastic Environmental Research and Risk Assessment*

abstract: 'Compositional data (CoDa) play an important role in many fields such as ecology, geology, and biology. The most widely used modeling approaches are based on the Dirichlet and the logistic-normal formulation under Aitchison geometry. Recent developments in simplex geometry allow regression models to be expressed in terms of coordinates and their coefficients to be estimated. Once the model is projected into real space, a multivariate Gaussian regression can be employed. However, most existing methods focus on linear models, and there is a lack of flexible alternatives such as additive or spatial models, especially within a Bayesian framework and with practical implementation details. In this work, we present a geoadditive regression model for CoDa from a Bayesian perspective using the brms package in R. The model applies the isometric log-ratio (ilr) transformation and penalized splines to incorporate nonlinear effects. We also propose two new Bayesian goodness-of-fit measures for CoDa regression: BR-CoDa-R² and BM-CoDa-R², extending the Bayesian R² to the compositional setting. These measures, alongside WAIC, support the descriptive assessment of explained variability and complement model evaluation. The methodology is validated through simulation studies and applied to predict soil texture composition in the Basque Country. Results demonstrate good performance, interpretable spatial patterns, and reliable quantification of explained variability in compositional outcomes.<br>
**Key words**<br> 
Bayesian inference; CoDa; Bayesian CoDa-R^2; Spatial modelling; Generalized additive models; penalized splines'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---


Find here the accompanying
[code repository](https://github.com/jmartinez-minaya/CoDabrms/) for the paper and attached in the article the Supplementary Information. 
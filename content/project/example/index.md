---
title: Bayesian Sample Selection
summary: This is a short summary of what I did for my maters thesis
tags:
- Bayesian Statistics
- Copula
date: "2020-12-15T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
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

Sample selection models are widely used to correct non-randomly selected data. By linking a binary selection equation with an outcome equation of interest, the induced bias can be corrected. We extend the Bayesian hierarchical two-part model by a multivariate hierarchy, enabling the presence of multiple dependent selection and outcome equations. Our estimation relies on a separation of correlations and variances to facilitate easier specification of prior knowledge. The separation also helps uphold the estimability restrictions for the probit selection equations. Assumptions of multivariate normality are limiting in many situations. We lift this restriction by replacing the likelihood with a multivariate Gaussian copula. The models presented are within a unified Bayesian framework and are evaluated using simulation studies with inference based on Markov Chain Monte Carlo simulation techniques. It can be shown that the copula based extension is better at estimating the parameters for the correlation matrix.

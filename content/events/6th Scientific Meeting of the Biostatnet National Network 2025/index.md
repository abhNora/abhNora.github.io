---
title: From real to Synthetic Data ensuring quality

event: 6th Scientific Meeting of the Biostatnet National Network 2025
event_url: https://eventos.adeit.es/123283/detail/national-biostatnet.html

location: ADEIT Fundación Universidad-Empresa de la Universidad de València
address:
  street: Plaza Virgen de la Paz, 3
  city: Ciutat Vella
  region: València
  postcode: '46001'
  country: Spain

summary: >-
  Poster presented during the Poster Session and Cocktail, accompanied by a 3-minute talk introducing the main ideas and contributions of the work on evaluating metrics for synthetic tabular data quality.

abstract: >-
  The growing reluctance to share original datasets and the increasing demand to comply with privacy regulations have motivated the adoption of synthetic data. Synthetic data replicates the statistical properties of the original datasets while ensuring that individual-level information or sensitive variables are not disclosed (Nowok et al., 2016; Raab et al., 2017). However, to effectively evaluate the quality of synthetic data, the development and refinement of validation metrics is required (Snoke et al., 2018; Raab et al., 2021). This assessment ensures the usability and reliability of synthetic datasets.   
  
  This research aims to introduce some existing validation metrics implemented in tools such as the synthpop package. The focus is on synthetic tabular data, with an emphasis on showcasing a comprehensive list of validation metrics that hold statistical significance and serve as a foundation for the development of new metrics. To address the challenges of validating synthetic data, the research highlights tailored methodologies for specific domains, such as energy, where there are unique challenges. Synthetic data offers opportunities to accelerate model training while ensuring compliance with privacy regulations. By developing robust metrics, the goal is to provide a practical framework for validating high-quality synthetic datasets that meet the needs of sensitive fields. These metrics will be presented to demonstrate their relevance and potential impact, ultimately addressing significant gaps in the literature concerning synthetic data validation in the energy sector.  
  
  As highlighted by Raab (2022), validation metrics can be categorized into three key dimensions: resemblance, utility, and privacy. Resemblance metrics, such as Propensity Score Mean-Squared Error (pMSE) or Kolmogorov-Smirnov Statistic (SPECKS), evaluate the similarity in the statistical distributions between the synthetic and original datasets. Utility metrics include measures like the Voas-Williamson Utility Measure (VW), which assess the suitability of synthetic data for specific analytical tasks, such as machine learning or statistical modeling. Privacy metrics ensure that sensitive information from the original data cannot be reconstructed or identified.


# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-01-15T18:00:00Z'
date_end: '2025-01-15T21:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2025-01-17T18:00:00Z'

authors:
  - admin

tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'BIOSTATNET2025'
  focal_point: Right

links:
  - type: slides
    url: Poster.pdf

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - example
---

---
title: "A fast marching eikonal solver for tilted transversely isotropic media"
authors:
- admin
author_notes:
- ""
- ""
date: "2020-08-01T00:00:00Z"
doi: "https://doi.org/10.1190/geo2019-0799.1"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Geophysics*"
publication_short: ""

abstract: Fast and accurate traveltime computation for quasi-P waves in anisotropic media is an essential ingredient of many seismic processing and interpretation applications such as Kirchhoff modeling and migration, microseismic source localization, traveltime tomography, etc. Fast sweeping methods are widely used for solving the anisotropic eikonal equation due to their flexibility for solving general equations compared to the fast marching method. However, it has been observed that fast sweeping can be much less efficient than fast marching for models with curved characteristics and practical grid sizes. By representing a tilted transversely isotropic (TTI) equation as a sequence of elliptically isotropic (EI) eikonal equations, we show that the fast marching algorithm can be used to compute fast and accurate traveltimes for TTI media. The tilt angle is absorbed into the description of the effective EI model and, therefore, the proposed approach does not compromise on the solution accuracy. Through tests on benchmark synthetic models, we test the proposed fast marching algorithm and show considerable improvement in accuracy by using factorization and second-order finite-difference stencil. The proposed methodology opens door to the possibility of using fast marching algorithm for a wider class of anisotropic eikonal equations.

# Summary. An optional shortened abstract.
summary:

tags:
- eikonal
featured: true

# links:
# - name: ""
#   url: ""
url_pdf:
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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

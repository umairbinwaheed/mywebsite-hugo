---
title: "First-arrival traveltime tomography for anisotropic media using the adjoint-state method"
authors:
- admin
- Garret Flagg
- Can Evren Yarman
author_notes:
- ""
- ""
date: "2015-07-01T00:00:00Z"
doi: "https://doi.org/10.1190/geo2015-0463.1"

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

abstract: Traveltime tomography using transmission data has been widely used for static corrections and for obtaining near-surface models for seismic depth imaging. More recently, it is also being used to build initial models for full-waveform inversion. The classic traveltime tomography approach based on ray tracing has difficulties in handling large data sets arising from current seismic acquisition surveys. Some of these difficulties can be addressed using the adjoint-state method, due to its low memory requirement and numerical efficiency. By coupling the gradient computation to nonlinear optimization, it avoids the need for explicit computation of the Fréchet derivative matrix. Furthermore, its cost is equivalent to twice the solution of the forward-modeling problem, irrespective of the size of the input data. The presence of anisotropy in the subsurface has been well established during the past few decades. The improved seismic images obtained by incorporating anisotropy into the seismic processing workflow justify the effort. However, previous literature on the adjoint-state method has only addressed the isotropic approximation of the subsurface. We have extended the adjoint-state technique for first-arrival traveltime tomography to vertical transversely isotropic (VTI) media. Because $\delta$ is weakly resolvable from surface seismic alone, we have developed the mathematical framework and procedure to invert for $v_{NMO}$ and $\eta$. Our numerical tests on the VTI SEAM model demonstrate the ability of the algorithm to invert for near-surface model parameters and reveal the accuracy achievable by the algorithm.

# Summary. An optional shortened abstract.
summary:

tags:
- traveltimes
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

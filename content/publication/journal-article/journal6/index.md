---
title: "An iterative, fast-sweeping-based eikonal solver for 3D tilted anisotropic media"
authors:
- admin
- Can Evren Yarman
- Garret Flagg
author_notes:
- ""
- ""
date: "2015-05-01T00:00:00Z"
doi: "https://doi.org/10.1190/geo2014-0375.1"

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

abstract: Computation of first-arrival traveltimes for quasi-P waves in the presence of anisotropy is important for high-end near-surface modeling, microseismic-source localization, and fractured-reservoir characterization — and it requires solving an anisotropic eikonal equation. Anisotropy deviating from elliptical anisotropy introduces higher order nonlinearity into the eikonal equation, which makes solving the eikonal equation a challenge. We addressed this challenge by iteratively solving a sequence of simpler tilted elliptically anisotropic eikonal equations. At each iteration, the source function was updated to capture the effects of the higher order nonlinear terms. We used Aitken’s extrapolation to speed up convergence rate of the iterative algorithm. The result is an algorithm for computing first-arrival traveltimes in tilted anisotropic media. We evaluated the applicability and usefulness of our method on tilted transversely isotropic media and tilted orthorhombic media. Our numerical tests determined that the proposed method matches the first arrivals obtained by wavefield extrapolation, even for strongly anisotropic and highly complex subsurface structures. Thus, for the cases where two-point ray tracing fails, our method can be a potential substitute for computing traveltimes. The approach presented here can be easily extended to compute first-arrival traveltimes for anisotropic media with lower symmetries, such as monoclinic or even the triclinic media.

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

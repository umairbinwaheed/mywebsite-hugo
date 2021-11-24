---
title: "A fast sweeping algorithm for accurate solution of the tilted transversely isotropic eikonal equation using factorization"
authors:
- admin
- Tariq Alkhalifah
author_notes:
- ""
- ""
date: "2017-11-01T00:00:00Z"
doi: "https://doi.org/10.1190/geo2016-0712.1"

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

abstract: Traveltime computation is essential for many seismic data processing applications and velocity analysis tools. High-resolution seismic imaging requires eikonal solvers to account for anisotropy whenever it significantly affects the seismic wave kinematics. Moreover, computation of auxiliary quantities, such as amplitude and take-off angle, relies on highly accurate traveltime solutions. However, the finite-difference-based eikonal solution for a point-source initial condition has upwind source singularity at the source position because the wavefront curvature is large near the source point. Therefore, all finite-difference solvers, even the high-order ones, show inaccuracies because the errors due to source-singularity spread from the source point to the whole computational domain. We address the source-singularity problem for tilted transversely isotropic (TTI) eikonal solvers using factorization. We solve a sequence of factored tilted elliptically anisotropic (TEA) eikonal equations iteratively, each time by updating the right-hand-side function. At each iteration, we factor the unknown TEA traveltime into two factors. One of the factors is specified analytically, such that the other factor is smooth in the source neighborhood. Through this iterative procedure, we obtain an accurate solution to the TTI eikonal equation. Numerical tests show significant improvement in accuracy due to factorization. The idea can be easily extended to compute accurate traveltimes for models with lower anisotropic symmetries, such as orthorhombic, monoclinic, or even triclinic media.

# Summary. An optional shortened abstract.
summary:

tags:
- wavefields
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

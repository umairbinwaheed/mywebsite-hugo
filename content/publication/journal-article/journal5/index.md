---
title: "Efficient traveltime solutions of the acoustic TI eikonal equation"
authors:
- admin
- Tariq Alkhalifah
- Hui Wang
author_notes:
- ""
- ""
date: "2015-02-01T00:00:00Z"
doi: "https://doi.org/10.1016/j.jcp.2014.11.006"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Computational Physics*"
publication_short: ""

abstract: Numerical solutions of the eikonal (Hamilton–Jacobi) equation for transversely isotropic (TI) media are essential for imaging and traveltime tomography applications. Such solutions, however, suffer from the inherent higher-order nonlinearity of the TI eikonal equation, which requires solving a quartic polynomial for every grid point. Analytical solutions of the quartic polynomial yield numerically unstable formulations. Thus, it requires a numerical root finding algorithm, adding significantly to the computational load. Using perturbation theory we approximate, in a first order discretized form, the TI eikonal equation with a series of simpler equations for the coefficients of a polynomial expansion of the eikonal solution, in terms of the anellipticity anisotropy parameter. Such perturbation, applied to the discretized form of the eikonal equation, does not impose any restrictions on the complexity of the perturbed parameter field. Therefore, it provides accurate traveltime solutions even for models with complex distribution of velocity and anisotropic anellipticity parameter, such as that for the complicated Marmousi model. The formulation allows for large cost reduction compared to using the direct TI eikonal solver. Furthermore, comparative tests with previously developed approximations illustrate remarkable gain in accuracy in the proposed algorithm, without any addition to the computational cost.

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

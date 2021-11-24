---
title: "Effective orthorhombic anisotropic models for wavefield extrapolation"
authors:
- Wilson Ibanez-Jacome
- Tariq Alkhalifah
- admin
author_notes:
- ""
- ""
date: "2014-07-01T00:00:00Z"
doi: "https://doi.org/10.1093/gji/ggu229"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Geophysical Journal International*"
publication_short: ""

abstract: Wavefield extrapolation in orthorhombic anisotropic media incorporates complicated but realistic models to reproduce wave propagation phenomena in the Earth's subsurface. Compared with the representations used for simpler symmetries, such as transversely isotropic or isotropic, orthorhombic models require an extended and more elaborated formulation that also involves more expensive computational processes. The acoustic assumption yields more efficient description of the orthorhombic wave equation that also provides a simplified representation for the orthorhombic dispersion relation. However, such representation is hampered by the sixth-order nature of the acoustic wave equation, as it also encompasses the contribution of shear waves. To reduce the computational cost of wavefield extrapolation in such media, we generate effective isotropic inhomogeneous models that are capable of reproducing the first-arrival kinematic aspects of the orthorhombic wavefield. First, in order to compute traveltimes in vertical orthorhombic media, we develop a stable, efficient and accurate algorithm based on the fast marching method. The derived orthorhombic acoustic dispersion relation, unlike the isotropic or transversely isotropic ones, is represented by a sixth order polynomial equation with the fastest solution corresponding to outgoing P waves in acoustic media. The effective velocity models are then computed by evaluating the traveltime gradients of the orthorhombic traveltime solution, and using them to explicitly evaluate the corresponding inhomogeneous isotropic velocity field. The inverted effective velocity fields are source dependent and produce equivalent first-arrival kinematic descriptions of wave propagation in orthorhombic media. We extrapolate wavefields in these isotropic effective velocity models using the more efficient isotropic operator, and the results compare well, especially kinematically, with those obtained from the more expensive anisotropic extrapolator.

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

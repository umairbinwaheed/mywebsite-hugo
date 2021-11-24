---
title: "A comparison of high-order explicit Runge–Kutta, extrapolation, and deferred correction methods in serial and parallel"
authors:
- David I. Ketcheson
- Umair bin Waheed
author_notes:
- ""
- ""
date: "2014-06-01T00:00:00Z"
doi: "http://dx.doi.org/10.2140/camcos.2014.9.175"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Communications in Applied Mathematics and Computational Science*"
publication_short: ""

abstract: We compare the three main types of high-order one-step initial value solvers - extrapolation, spectral deferred correction, and embedded Runge–Kutta pairs. We consider orders four through twelve, including both serial and parallel implementations. We cast extrapolation and deferred correction methods as fixed-order Runge–Kutta methods, providing a natural framework for the comparison. The stability and accuracy properties of the methods are analyzed by theoretical measures, and these are compared with the results of numerical tests. In serial, the eighth-order pair of Prince and Dormand (DOP8) is most efficient. But other high-order methods can be more efficient than DOP8 when implemented in parallel. This is demonstrated by comparing a parallelized version of the well-known ODEX code with the (serial) DOP853 code. For an $N$-body problem with $N=400$, the experimental extrapolation code is as fast as the tuned Runge–Kutta pair at loose tolerances, and is up to two times as fast at tight tolerances.

# Summary. An optional shortened abstract.
summary:

tags:
-
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

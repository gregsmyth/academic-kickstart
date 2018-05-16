+++
title = "Trajectory optimization for dynamic couch rotation during volumetric modulated arc radiotherapy"
date = 2013-11-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Gregory Smyth", "Jeffrey C Bamber", "Philip M Evans", "James L Bedford"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "In *Physics in Medicine and Biology*"
publication_short = "In *Phys. Med. Biol.*"

# Abstract and optional shortened version.
abstract = "Non-coplanar radiation beams are often used in three-dimensional conformal and intensity modulated radiotherapy to reduce dose to organs at risk (OAR) by geometric avoidance. In volumetric modulated arc radiotherapy (VMAT) non-coplanar geometries are generally achieved by applying patient couch rotations to single or multiple full or partial arcs. This paper presents a trajectory optimization method for a non-coplanar technique, dynamic couch rotation during VMAT (DCR–VMAT), which combines ray tracing with a graph search algorithm. Four clinical test cases (partial breast, brain, prostate only, and prostate and pelvic nodes) were used to evaluate the potential OAR sparing for trajectory-optimized DCR–VMAT plans, compared with standard coplanar VMAT. In each case, ray tracing was performed and a cost map reflecting the number of OAR voxels intersected for each potential source position was generated. The least-cost path through the cost map, corresponding to an optimal DCR–VMAT trajectory, was determined using Dijkstra's algorithm. Results show that trajectory optimization can reduce dose to specified OARs for plans otherwise comparable to conventional coplanar VMAT techniques. For the partial breast case, the mean heart dose was reduced by 53%. In the brain case, the maximum lens doses were reduced by 61% (left) and 77% (right) and the globes by 37% (left) and 40% (right). Bowel mean dose was reduced by 15% in the prostate only case. For the prostate and pelvic nodes case, the bowel V50 Gy and V60 Gy were reduced by 9% and 45% respectively. Future work will involve further development of the algorithm and assessment of its performance over a larger number of cases in site-specific cohorts."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["dvr-vmat"]

# Links (optional).
url_pdf = "http://iopscience.iop.org/article/10.1088/0031-9155/58/22/8163/meta"
url_preprint = "http://epubs.surrey.ac.uk/806909/"


# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++

More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code.

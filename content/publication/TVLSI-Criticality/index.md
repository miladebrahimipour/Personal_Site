---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Aging and Process Variation-aware Statistical Gate Sizing using Incremental-based Criticality Computation"
authors: [Seyed Milad Ebrahimipour, Behnam Ghavami, Mohsen Raji]
date: Under Review
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-10-31T12:14:19+03:30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Very Large Scale Integration"
publication_short: "IEEE TVLSI **(Under Review)**"

abstract: "As CMOS devices become smaller, aging-induced and process variations become major issues for circuit reliability. In this paper, a statistical gate sizing method is proposed to improve the lifetime reliability of manufactured chips in presence of process variations and aging effects. To this end, we propose a canonical first order delay model to estimate the delay degradation of a gate under Negative Bias Temperature Instability (NBTI) and Process Variations (PV) considering spatial correlations. Using the proposed gate delay model, a Statistical Static Timing Analysis method is introduced to compute the circuit delay considering the joint effect of process variation and NBTI. To guarantee that the circuit meets the required timing constraints, we propose an incremental gate sizing technique. This technique first computes the criticality of each gate defined as the probability that a gate lies on the critical path due to NBTI and process variations. Then, a group of gates with the highest ranking according to criticality is chosen for gate sizing-based timing optimization. It is worthy to note that, by using the proposed statistical gate delay model, we can compute criticality of each gate incrementally. Experimental results based on ISCAS’85 benchmark circuits show that the proposed method can improve the lifetime reliability defined as $1.1(\\mu + 3\\sigma)$ of the initial delay distribution of the circuit at the expense of 8.64% area overhead. In comparison with the path-based method, the proposed approach is much faster, especially for larger circuits, which makes it a viable solution to optimize the lifetime reliability trade-off of very large-scale circuits used in industry. **(Under Review)**"

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code: https://github.com/miladebrahimipour/Adaam_ICCAD2020
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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

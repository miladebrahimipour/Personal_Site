---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Aadam: A Fast, Accurate, and Versatile Aging-Aware Cell Library Delay Model using Feed-Forward Neural Network"
authors: [Seyed Milad Ebrahimipour, Behnam Ghavami, Hamid Mousavi, Mohsen Raji, Zhenman Fang, Lesley Shannon]
date: 2020-11-02
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-10-19T13:26:39+03:30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE/ACM Inetrnational Conference on Computer-Aided Design"
publication_short: "ICCAD"

abstract: "With the CMOS technology scaling, transistor aging has become one major issue affecting circuit reliability and lifetime. There are two major classes of existing studies that model the aging effects in the circuit delay. One is at transistor-level, which is highly accurate but very slow. The other is at gate-level, which is faster but less accurate. Moreover, most prior studies only consider a limited subset or limited value ranges of aging factors.

In this paper, we propose Aadam, a fast, accurate, and versatile aging-aware delay model for generic cell libraries. In Aadam, we first use transistor-level SPICE simulations to accurately characterize the delay degradation of each library cell under a versatile set of aging factors, including both physical parameters (i.e., initial threshold voltage and transistor width/length ratio) and operating conditions (i.e., working temperature, signal probability, input signal slew range, output load capacitance range, and projected lifetime). For each library cell, we then train a feed-forward neural network (FFNN) to learn the relation between the input aging factors and output cell delay degradation. Therefore, for a given input circuit and a given combination of aging factors, we can use the trained FFNNs to quickly and accurately infer the delay degradation for each gate in the circuit. Finally, to effectively estimate the aging-aware lifetime delay of large-scale circuits, we also integrate Aadam into a state-of-the-art static timing analysis tool called OpenTimer. Experimental results demonstrate that Aadam achieves fast estimation of the aging-induced delay with high accuracy close to transistor-level simulation."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: http://www.sfu.ca/~zhenman/files/C21-ICCAD2020-Aadam.pdf
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

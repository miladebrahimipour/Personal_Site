---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "LEAP: A Deep Learning based Aging-Aware Architecture Exploration Framework for FPGAs"
authors: [Seyed Milad Ebrahimipour, Behnam Ghavami, Zhenman Fang, Lesley Shannon]
date: 2021-02-02
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-10-31T10:16:47+03:30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ACM/SIGDA International Symposium on Field-Programmable Gate Arrays"
publication_short: "FPGA **(Under Review)**"

abstract: "Transistor aging raises a vital lifetime reliability challenge for FPGAdevices in advanced technology nodes, which could lead to theperformance loss or timing failure of FPGA designs over the time.Most existing studies use transistor-level simulation to analyze theaging impact on FPGA architecture choices, which is impracticalfor modern FPGAs that have billions of transistors.

In this paper, we design and implement an open-source toolcalled LEAP to enable the aging-aware FPGA architecture explo-ration. The core idea of LEAP is to efficiently model the aging-induced delay degradation at the coarse-grained FPGA basic blocklevel using deep neural networks (DNNs), while achieving almostthe same accuracy as the transistor-level simulation. For each typeof the FPGA basic block such as LUT and DSP, we first characterizeits accurate delay degradation via transistor-level SPICE simula-tion under a versatile set of aging factors from the FPGA fabricand in-field operation. Then we train one DNN model for eachblock type to learn the relation between its delay degradation andaging factors. Moreover, we integrate our DNN models into thewidely used Verilog-to-Routing (VTR 8) toolflow and generate theaging-aware FPGA architecture file. Finally, we develop the aging-aware static timing analysis to support analyzing the aging impacton the entire FPGA circuit. Experimental results demonstrate thatLEAP can predict the delay degradation of FPGA blocks more than104x to107x faster than transistor-level SPICE simulation, with themaximum prediction error of less than 0.7%. Case studies are con-ducted to demonstrate that an FPGA architect can leverage LEAP toexplore better aging-aware FPGA architectures and an end-usercan leverage LEAP to better protect the FPGA design against agingwith accurate timing guardband. **(Under Review)**"

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

url_pdf:
url_code:
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

---
title: "Efficient Spatio-Temporal Video Grounding with Semantic-Guided Feature Decomposition"

summary: patio-temporal video grounding (STVG) aims to localize the spatiotemporal object tube in a video according to a given text query.....

tags:
- Video Content Analysis
date: "2023-10-13T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

# image:
#   caption: Photo by rawpixel on Unsplash
#   focal_point: Smart

links:
- name: PDF
  url: https://dl.acm.org/doi/abs/10.1145/3581783.3612441
- name: CODE
  url: https://github.com/TJUMMG/SGFDN
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

### **Abstract:**

​		Spatio-temporal video grounding (STVG) aims to localize the spatiotemporal object tube in a video according to a given text query. Current approaches address the STVG task with end-to-end frameworks while suffering from heavy computational complexity and insufficient spatio-temporal interactions. To overcome these limitations, we propose a novel Semantic-Guided Feature Decomposition based Network (SGFDN). A semantic-guided mapping operation is proposed to decompose the 3D spatio-temporal feature into 2D motions and 1D object embedding without losing much object-related semantic information. Thus, the computational complexity in computationally expensive operations such as attention mechanisms can be effectively reduced by replacing the input spatio-temporal feature with the decomposed features. Furthermore, based on this decomposition strategy, a pyramid relevance filtering based attention is proposed to capture the crossmodal interactions at multiple spatio-temporal scales. In addition, a decomposition-based grounding head is proposed to locate the queried objects with less computational complexity. Extensive experiments on two widely-used STVG datasets (VidSTG and HCSTVG) demonstrate that our method enjoys state-of-the-art performance as well as less computational complexity.

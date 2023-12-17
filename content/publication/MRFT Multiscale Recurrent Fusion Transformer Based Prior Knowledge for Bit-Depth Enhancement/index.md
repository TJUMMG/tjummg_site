---
title: "MRFT: Multiscale Recurrent Fusion Transformer Based Prior Knowledge for Bit-Depth Enhancement"
authors:
- Xin Wen, Weizhi Nie
- admin
- Yuting Su

date: "2023-03-22T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Circuits and Systems for Video Technology"
publication_short:

abstract: Bit-depth enhancement (BDE) plays an important role in providing high bit-depth data support for high-dynamic range (HDR) display. Although convolutional neural network (CNN) based BDE methods have achieved top performance, multiscale feature extraction and fusion still suffer from some inherent architectural flaws. Moreover, the training-data-scarce scene has not been effectively explored. To this end, this paper proposes an innovative multiscale recurrent fusion transformer (MRFT) framework, which contains three key components, i.e. multiscale transformer feature encoder, recurrent feature fusion module, and prior knowledge injection. Specifically, the multiscale transformer feature encoder consists of a prior-injected context encoder (PICE) and a multiscale local feature encoder (MLFE). PICE leverages the vanilla self-attention mechanism to extract the global context correlating spatially-distant contents for distinguishing long-distance false contours. MLFE exploits the local self-attention mechanism with varied window sizes to capture different-scale detail features. Then, a hierarchical recurrent decoder (HRD) is proposed as the recurrent feature fusion module to fuse multiscale visual information with global guidance. Via the circular query-key mechanism, global-to-local information is progressively fused. Furthermore, we propose a two-stage alternating optimization strategy for prior knowledge injection. By pre-parameterizing the global auxiliary priors, the training dilemma on the data-scarce domain is significantly alleviated. Extensive analyses on multiple benchmark datasets demonstrate the superiority of our MRFT in terms of quantitative measures and aesthetic effects.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Bit-depth enhancement
featured: false

links:
 - name: PDF
   url: https://ieeexplore.ieee.org/document/10078331/keywords#keywords
 - name: CODE
   url: https://github.com/TJUMMG/MRFT
# url_pdf: https://ieeexplore.ieee.org/document/10078331/keywords#keywords
# url_code: https://github.com/TJUMMG/MRFT
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---




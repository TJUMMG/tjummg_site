---
title: "Residual-Guided Multiscale Fusion Network for Bit-Depth Enhancement"
authors:
- admin
- Xin Wen, Weizhi Nie, Yuting Su, Peiguang Jing, Xiaokang Yang

date: "2021-07-20T00:00:00Z"
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

abstract: Bit-depth enhancement (BDE) is a challenging task due to stubborn false contour artifacts and disappeared detailed information. Given the mixture of structural distortions and real edges in low bit-depth (LBD) images, both large and small receptive fields (RFs) are critical for BDE tasks. However, even powerful state-of-the-art CNN-based methods can hardly capture sufficient LBD features under multiple RFs. This paper proposes a residual-guided multiscale fusion network (RMFNet) to explore multiscale features in a residual manner. We find that the shuffling operation provides desired multiscale inputs for effectively distinguishing false contours from real edges without any loss of information. Therefore, we shuffle LBD images to multiple scales and then fully extract residual features under different RFs with corresponding subnets. To facilitate interscale guidance from the global context to the local context, we progressively transfer the encoded residual features between adjacent subnets from top to bottom. We further propose a dual-branch depthwise group fusion (DDGF) module to fully capture inter- and inner correlations of multiscale features with fewer parameters. Finally, extensive experiments show that our algorithm achieves excellent performance improvement both quantitatively and qualitatively, verifying its effectiveness.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Bit-depth enhancement
featured: false

links:
 - name: PDF
   url: https://ieeexplore.ieee.org/document/9491068/keywords#keywords
 - name: CODE
   url: https://github.com/TJUMMG/RMFNet
# url_pdf: https://ieeexplore.ieee.org/document/9491068/keywords#keywords
# url_code: https://github.com/TJUMMG/RMFNet
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




---
title: "TANet: Target Attention Network for Video Bit-Depth Enhancement"
authors:
- admin
- Ziwen Yang, Yuting Su, Xiaokang Yang

date: "2021-09-24T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Multimedia"
publication_short:

abstract: Video bit-depth enhancement (VBDE) reconstructs high-bit-depth (HBD) frames from a low-bit-depth (LBD) video sequence. As neighboring frames contain a considerable amount of complementary information related to the center frame, it is vital for VBDE to exploit neighboring frames as much as possible. Conventional VBDE algorithms with explicit alignment across frames attempt to warp each neighboring frame to the center frame with estimated optical flow, taking into account only pairwise correlation. Most spatiotemporal fusion approaches involve direct concatenation or 3D convolution and treat all features equally, failing to focus on information related to the center frame. Therefore, in this paper, we introduce an improved nonlocal block as a global attentive alignment (GAA) module, which takes the whole input video sequence into consideration to capture features that are globally correlated, to perform implicit alignment. Furthermore, given the bulk of features extracted from the center and neighboring frames, we propose target-guided attention (TGA). TGA can exploit more center-frame-related details and facilitate feature fusion. The proposed network (dubbed TANet) is capable of effectively eliminating false contours and recovering the center frame in high quality, as demonstrated by the experimental results. TANet outperforms state-of-the-art models in terms of both PSNR and SSIM with low time consumption.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Video bit-depth enhancement
featured: false

links:
 - name: PDF
   url: https://ieeexplore.ieee.org/document/9547837
# url_pdf: https://ieeexplore.ieee.org/document/9547837
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




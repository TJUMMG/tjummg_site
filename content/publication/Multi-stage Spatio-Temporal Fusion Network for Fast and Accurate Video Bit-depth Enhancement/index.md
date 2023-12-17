---
title: "Multi-stage Spatio-Temporal Fusion Network for Fast and Accurate Video Bit-depth Enhancement"
authors:
- admin
- Zhiwei Fan, Ziwen Yang, Yuting Su, Xiaokang Yang
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2023-07-16T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-07-17T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Multimedia"
publication_short: ""

abstract: For video bit-depth enhancement (VBDE) tasks, inter-frame information is critical for removing false contours and recovering the details in low bit-depth (LBD) videos. However, due to different structural distortions and complex motions in the neighboring frames, it is difficult to effectively utilized inter-frame information. Most algorithms rely on alignment operations to provide information of neighboring frames, suffering from slow inference speed due to the complex alignment module design. Meanwhile, most existing methods sequentially perform the intra-frame feature extractions and inter-frame information fusions, but fail to efficiently fuse spatio-temporal information. Therefore, in this paper, we propose a two-stage progressive group (TSPG) network to find complementary information related to the target frame without adopting an alignment operation. To simultaneously achieve intra-frame feature extractions and inter-frame feature fusions, we propose a parallel spatio-temporal fusion (PSTF) module with a dual-branch spatial-temporal residual (DSTR) block to focus on more useful temporal information while ensuring a faster inference speeds. Extensive experiments on public datasets demonstrate that our proposed multi-stage spatio-temporal fusion network (named MSTFN) can quickly and effectively eliminate false contours and recover high quality target frames. Furthermore, our method outperforms the state-of-the-art methods in terms of both PSNR and SSIM, and can reach faster inference speeds.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Video bit-depth enhancement
featured: false

links:
 - name: PDF
   url: https://ieeexplore.ieee.org/abstract/document/10185099/keywords#keywords
 - name: CODE
   url: https://github.com/TJUMMG/MSTFN
# url_pdf: https://ieeexplore.ieee.org/abstract/document/10185099/keywords#keywords
# url_code: https://github.com/TJUMMG/MSTFN
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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

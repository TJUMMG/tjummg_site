---
title: "Multi-stage Spatio-Temporal Fusion Network for Fast and Accurate Video Bit-depth Enhancement"

summary: For video bit-depth enhancement (VBDE) tasks, inter-frame information is critical for removing false contours and recovering the details in low bit-depth (LBD) video, .....

# 所有类别在/home/projects.md里面定义，里面的tags定义了三种类型
tags:
- Imagevideo Processing
date: "2023-07-16T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

# image:
#   caption: Photo by rawpixel on Unsplash
#   focal_point: Smart

links:
- name: PDF
  url: https://ieeexplore.ieee.org/abstract/document/10185099/keywords#keywords
- name: CODE
  url: https://github.com/TJUMMG/MSTFN
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

​		For video bit-depth enhancement (VBDE) tasks, inter-frame information is critical for removing false contours and recovering the details in low bit-depth (LBD) videos. However, due to different structural distortions and complex motions in the neighboring frames, it is difficult to effectively utilized inter-frame information. Most algorithms rely on alignment operations to provide information of neighboring frames, suffering from slow inference speed due to the complex alignment module design. Meanwhile, most existing methods sequentially perform the intra-frame feature extractions and inter-frame information fusions, but fail to efficiently fuse spatio-temporal information. Therefore, in this paper, we propose a two-stage progressive group (TSPG) network to find complementary information related to the target frame without adopting an alignment operation. To simultaneously achieve intra-frame feature extractions and inter-frame feature fusions, we propose a parallel spatio-temporal fusion (PSTF) module with a dual-branch spatial-temporal residual (DSTR) block to focus on more useful temporal information while ensuring a faster inference speeds. Extensive experiments on public datasets demonstrate that our proposed multi-stage spatio-temporal fusion network (named MSTFN) can quickly and effectively eliminate false contours and recover high quality target frames. Furthermore, our method outperforms the state-of-the-art methods in terms of both PSNR and SSIM, and can reach faster inference speeds.

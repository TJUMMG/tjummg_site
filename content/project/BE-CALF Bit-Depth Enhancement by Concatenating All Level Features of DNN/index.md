---
title: "BE-CALF: Bit-Depth Enhancement by Concatenating All Level Features of DNN"

summary: There is a growing demand for monitors to provide high-quality visualization with more bits representing each rendered pixel. However, since most existing images and videos are of low bit-depth .....

# 所有类别在/home/projects.md里面定义，里面的tags定义了三种类型
tags:
- Imagevideo Processing
date: "2019-05-16T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

# image:
#   caption: Photo by rawpixel on Unsplash
#   focal_point: Smart

links:
- name: PDF
  url: https://ieeexplore.ieee.org/document/8713480
- name: CODE
  url: https://github.com/TJUMMG/BE-CALF
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

​		There is a growing demand for monitors to provide high-quality visualization with more bits representing each rendered pixel. However, since most existing images and videos are of low bit-depth (LBD), transforming LBD images to visually pleasant high bit-depth (HBD) versions is of significant value. Most existing bit-depth enhancement methods generate unsatisfactory HBD images with annoying false contour artifacts or blurry details, and some algorithms are also time-consuming. To overcome these drawbacks, we propose a bit-depth enhancement framework via concatenating all level features of deep neural networks (DNNs). A novel deep learning network is proposed based on the deep convolutional variational auto-encoders (VAEs), and skip connections that concatenate every two layers are applied to pass low-level and high-level features to consequent layers, easing the gradient vanishing problem. Meanwhile, the proposed network is optimized to generate the residual between original images and its quantized ones, which performs better than recovering HBD images directly. The experimental results show that the proposed algorithm can eliminate false contour artifacts of the recovered HBD images with low time consumption, and can achieve dramatic restoration performance gains compared with state-of-the-art methods both subjectively and objectively.

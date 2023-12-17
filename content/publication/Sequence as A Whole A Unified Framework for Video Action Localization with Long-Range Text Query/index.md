---
title: "Sequence as A Whole: A Unified Framework for Video Action Localization with Long-Range Text Query"
authors:
- Yuting Su, Weikang Wang 
- admin
- Shuang Ma, Xiaokang Yang
date: "2023-02-13T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Image Processing"
publication_short: ""

abstract: Comprehensive understanding of video content requires both spatial and temporal localization. However, there lacks a unified video action localization framework, which hinders the coordinated development of this field. Existing 3D CNN methods take fixed and limited input length at the cost of ignoring temporally long-range cross-modal interaction. On the other hand, despite having large temporal context, existing sequential methods often avoid dense cross-modal interactions for complexity reasons. To address this issue, in this paper, we propose a unified framework which handles the whole video in sequential manner with long-range and dense visual-linguistic interaction in an end-to-end manner. Specifically, a lightweight relevance filtering based transformer (Ref-Transformer) is designed, which is composed of relevance filtering based attention and temporally expanded MLP. The text-relevant spatial regions and temporal clips in video can be efficiently highlighted through the relevance filtering and then propagated among the whole video sequence with the temporally expanded MLP. Extensive experiments on three sub-tasks of referring video action localization, i.e., referring video segmentation, temporal sentence grounding, and spatiotemporal video grounding, show that the proposed framework achieves the state-of-the-art performance in all referring video action localization tasks.

# Summary. An optional shortened abstract.
summary: Comprehensive understanding of video content requires both spatial and temporal localization. However, there lacks a unified video action localization framework, which hinders the coordinated development of this field. Existing 3D CNN methods take fixed and limited input length at the cost of ignoring temporally long-range cross-modal interaction. On the other hand, despite having large temporal context, existing sequential methods often avoid dense cross-modal interactions for complexity reasons. To address this issue, in this paper, we propose a unified framework which handles the whole video in sequential manner with long-range and dense visual-linguistic interaction in an end-to-end manner. Specifically, a lightweight relevance filtering based transformer (Ref-Transformer) is designed, which is composed of relevance filtering based attention and temporally expanded MLP. The text-relevant spatial regions and temporal clips in video can be efficiently highlighted through the relevance filtering and then propagated among the whole video sequence with the temporally expanded MLP.

tags:
- Referring video segmentation
featured: true

links:
 - name: PDF
   url: https://ieeexplore.ieee.org/document/10043827/keywords#keywords
 - name: CODE
   url: https://github.com/TJUMMG/SAW

# url_pdf: https://ieeexplore.ieee.org/document/10043827/keywords#keywords
# url_code: https://github.com/TJUMMG/SAW
# url_dataset: ' '
# url_poster: ' '
# url_project: ''
# url_slides: ''
# url_source: ' '
# url_video: ' '

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
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

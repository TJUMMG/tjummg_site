---
# 论文名字
title: "Knowledge-Enhanced Causal Reinforcement Learning Model for Interactive Recommendation"

# 作者
authors:
- Weizhi Nie, Xin Wen
- admin
- Jiawei Chen, Jiancan Wu, Guoqing Jin, Jing Lu, An-An Liu

# 日期
date: "2023-05-16T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# 论文类别
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# 论文期刊名称
# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Multimedia"
publication_short:

# 摘要
abstract: Owing to its inherently dynamic nature and economical training cost, offline reinforcement learning (RL) is typically employed to implement an interactive recommender system (IRS). A crucial challenge in offline RL-based IRSs is the data sparsity issue, i.e. , it is hard to mine user preferences well from the limited number of user-item interactions. In this paper, we propose a knowledge-enhanced causal reinforcement learning model (KCRL) to mitigate data sparsity in IRSs. We make technical extensions to the offline RL framework in terms of the reward function and state representation. Specifically, we first propose a group preference-injected causal user model (GCUM) to learn user satisfaction ( i.e. , reward) estimation. We introduce beneficial group preference information, namely, the group effect, via causal inference to compensate for incomplete user interests extracted from sparse data. Then, we learn the RL recommendation policy with the reward given by the GCUM. We propose a knowledge-enhanced state encoder (KSE) to generate knowledge-enriched user state representations at each time step, which is assisted by a self-constructed user-item knowledge graph. Extensive experimental results on real-world datasets demonstrate that our model significantly outperforms the baselines.

# 简要介绍
# Summary. An optional shortened abstract.
summary: Owing to its inherently dynamic nature and economical training cost, offline reinforcement learning (RL) is typically employed to implement an interactive recommender system (IRS). A crucial challenge in offline RL-based IRSs is the data sparsity issue, i.e. , it is hard to mine user preferences well from the limited number of user-item interactions. In this paper, we propose a knowledge-enhanced causal reinforcement learning model (KCRL) to mitigate data sparsity in IRSs. We make technical extensions to the offline RL framework in terms of the reward function and state representation. Specifically, we first propose a group preference-injected causal user model (GCUM) to learn user satisfaction ( i.e. , reward) estimation. We introduce beneficial group preference information, namely, the group effect, via causal inference to compensate for incomplete user interests extracted from sparse data. Then, we learn the RL recommendation policy with the reward given by the GCUM. We propose a knowledge-enhanced state encoder (KSE) to generate knowledge-enriched user state representations at each time step, which is assisted by a self-constructed user-item knowledge graph.

# 类别标签
tags:
- Interactive recommender system
# featured: false

# 论文链接和代码链接
links:
 - name: PDF
   url: https://ieeexplore.ieee.org/document/10125070/keywords#keywords
 # - name: CODE
 #   url: https://ieeexplore.ieee.org/document/10125070/keywords#keywords

# 下面这些不要改
# url_pdf: ''
# url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# 是否放图片
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: true

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




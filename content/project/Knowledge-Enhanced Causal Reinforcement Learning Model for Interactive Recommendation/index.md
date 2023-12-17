---
title: Knowledge-Enhanced Causal Reinforcement Learning Model for Interactive Recommendation

summary: Owing to its inherently dynamic nature and economical training cost, offline reinforcement learning (RL) is typically employed to implement an interactive recommender system (IRS)......

tags:
- Recommendation Systems
date: "2023-05-16T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

# image:
#   caption: Photo by rawpixel on Unsplash
#   focal_point: Smart

links:
- name: PDF
  url: https://ieeexplore.ieee.org/document/10125070/keywords#keywords
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

​		Owing to its inherently dynamic nature and economical training cost, offline reinforcement learning (RL) is typically employed to implement an interactive recommender system (IRS). A crucial challenge in offline RL-based IRSs is the data sparsity issue, i.e. , it is hard to mine user preferences well from the limited number of user-item interactions. In this paper, we propose a knowledge-enhanced causal reinforcement learning model (KCRL) to mitigate data sparsity in IRSs. We make technical extensions to the offline RL framework in terms of the reward function and state representation. Specifically, we first propose a group preference-injected causal user model (GCUM) to learn user satisfaction ( i.e. , reward) estimation. We introduce beneficial group preference information, namely, the group effect, via causal inference to compensate for incomplete user interests extracted from sparse data. Then, we learn the RL recommendation policy with the reward given by the GCUM. We propose a knowledge-enhanced state encoder (KSE) to generate knowledge-enriched user state representations at each time step, which is assisted by a self-constructed user-item knowledge graph. Extensive experimental results on real-world datasets demonstrate that our model significantly outperforms the baselines.

---
permalink: /kdd21-seanet
hidden: true
classes: wide
# layout: single-hf
layout: single
title: KDD21 Deep Learning Embeddings for Data Series Similarity Search
author_profile: true
last_modified_at: 2021-08-05
redirect_from: 
  - /kdd21-seanet.html
# excerpt: "Minimal Mistakes is a flexible two-column Jekyll theme."
# layouts_gallery:
#   - url: /assets/images/mm-layout-splash.png
#     image_path: /assets/images/mm-layout-splash.png
#     alt: "splash layout example"
#   - url: /assets/images/mm-layout-single-meta.png
#     image_path: /assets/images/mm-layout-single-meta.png
#     alt: "single layout with comments and related posts"
#   - url: /assets/images/mm-layout-archive.png
#     image_path: /assets/images/mm-layout-archive.png
#     alt: "archive layout example"
# toc: true
---

## Abstract

A key operation for the (increasingly large) data series collection analysis is similarity search. According to recent studies, SAX-based indexes offer state-of-the-art performance for similarity search tasks. However, their performance lags under high-frequency, weakly correlated, excessively noisy, or other dataset-specific properties. In this work, we propose Deep Embedding Approximation (DEA), a novel family of data series summarization techniques based on deep neural networks. Moreover, we describe SEAnet, a novel architecture especially designed for learning DEA, that introduces the Sum of Squares preservation property into the deep network design. Finally, we propose a new sampling strategy, SEASam, that allows SEAnet to effectively train on massive datasets. Comprehensive experiments on 7 diverse synthetic and real datasets verify the advantages of DEA learned using SEAnet, when compared to other state-of-the-art traditional and DEA solutions, in providing high- quality data series summarizations and similarity search results.

## Codes

| SEAnet architecture | https://github.com/qtwang/SEAnet |
| Indexing & query answering | https://github.com/qtwang/isax-modularized |

## Datasets

| Astro (astrophysics) | https://swift.gsfc.nasa.gov/results/bs58mon/ |
| Deep1B (computer vision) | http://sites.skoltech.ru/compvision/noimi |
| SALD (neuroscience) | http://fcon_1000.projects.nitrc.org/indi/retro/sald.html |
| Seismic (seismology) | http://ds.iris.edu/data/access/ |

## Cite this work

```latex
@inproceedings{kdd21-Wang-SEAnet,
  author    = {Wang, Qitong and 
               Palpanas, Themis},
  title     = {Deep Learning Embeddings for Data Series Similarity Search},
  booktitle = {KDD'21: The 27th ACM SIGKDD Conference on Knowledge Discovery and Data Mining, Virtual Event, Singapore, August 14-18, 2021},
  publisher = {ACM},
  year      = {2021},
  url       = {https://doi.org/10.1145/3447548.3467317},
  doi       = {10.1145/3447548.3467317},
  timestamp = {Thu, 05 Aug 2021 09:46:47 +0800}
}
```
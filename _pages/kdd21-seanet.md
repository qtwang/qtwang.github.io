---
permalink: /kdd21-seanet
hidden: true
classes: wide
# layout: single-hf
# layout: single
layout: single-comments
title: "Deep Learning Embeddings for Data Series Similarity Search"
author_profile: true
last_modified_at: 2022-06-05
redirect_from: 
  - /seanet
  - /seanet.html
  - /kdd21-seanet
  - /kdd21-seanet.html
excerpt: "ACM SIGKDD 2021"
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
# comments: true
---

[Qitong Wang](https://qtwang.github.io/) and [Themis Palpanas](http://helios.mi.parisdescartes.fr/~themisp/home.html), published in [ACM SIGKDD 2021](https://www.kdd.org/kdd2021/)

## Abstract

A key operation for the (increasingly large) data series collection analysis is similarity search. According to recent studies, SAX-based indexes offer state-of-the-art performance for similarity search tasks. However, their performance lags under high-frequency, weakly correlated, excessively noisy, or other dataset-specific properties. In this work, we propose Deep Embedding Approximation (DEA), a novel family of data series summarization techniques based on deep neural networks. Moreover, we describe SEAnet, a novel architecture especially designed for learning DEA, that introduces the Sum of Squares preservation property into the deep network design. Finally, we propose a new sampling strategy, SEASam, that allows SEAnet to effectively train on massive datasets. Comprehensive experiments on 7 diverse synthetic and real datasets verify the advantages of DEA learned using SEAnet, when compared to other state-of-the-art traditional and DEA solutions, in providing high- quality data series summarizations and similarity search results.

## Materials

| Paper in [KDD21](/assets/pdf/kdd21-seanet.pdf), [VLDB22 PhD Workshop](/assets/pdf/vldb22phdws-seanet.pdf) |
| Slides at [KDD21](/assets/pdf/kdd21-seanet-slides.pdf) |
| Talk at [KDD21](/assets/video/kdd21-seanet.mp4), [Tsinghua AI Time PhD Forum (in Chinese)](https://www.bilibili.com/video/BV1ub4y1Y7NW?t=1676.4) |

## Codes

| [SEAnet architecture](https://github.com/qtwang/SEAnet) |
| [Indexing & query answering](https://github.com/qtwang/isax-modularized) |

## Datasets

| [Astro](https://swift.gsfc.nasa.gov/results/bs58mon/) (astrophysics) |
| [Deep1B](http://sites.skoltech.ru/compvision/noimi) (computer vision) |
| [SALD](http://fcon_1000.projects.nitrc.org/indi/retro/sald.html) (neuroscience) |  |
| [Seismic](http://ds.iris.edu/data/access/) (seismology) |

## Cite this work

| BibTex | [bib](/assets/bib/kdd21-seanet-acm.bib) |
| ACM Ref | Qitong Wang and Themis Palpanas. 2021. Deep Learning Embeddings for Data Series Similarity Search. In Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery & Data Mining (KDD'21). Association for Computing Machinery, New York, NY, USA, 1708–1716. DOI:https://doi.org/10.1145/3447548.3467317 |

---
permalink: /kdd21-seanet
hidden: true
classes: wide
# layout: single-hf
layout: single
# layout: single-comments
title: "Deep Learning Embeddings for Data Series Similarity Search"
author_profile: true
last_modified_at: 2021-08-05
redirect_from: 
  - /seanet
  - /seanet.html
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
comments: true
---

[Qitong Wang](https://qtwang.github.io/) and [Themis Palpanas](http://helios.mi.parisdescartes.fr/~themisp/home.html), published in [ACM SIGKDD 2021](https://www.kdd.org/kdd2021/)

## Abstract

A key operation for the (increasingly large) data series collection analysis is similarity search. According to recent studies, SAX-based indexes offer state-of-the-art performance for similarity search tasks. However, their performance lags under high-frequency, weakly correlated, excessively noisy, or other dataset-specific properties. In this work, we propose Deep Embedding Approximation (DEA), a novel family of data series summarization techniques based on deep neural networks. Moreover, we describe SEAnet, a novel architecture especially designed for learning DEA, that introduces the Sum of Squares preservation property into the deep network design. Finally, we propose a new sampling strategy, SEASam, that allows SEAnet to effectively train on massive datasets. Comprehensive experiments on 7 diverse synthetic and real datasets verify the advantages of DEA learned using SEAnet, when compared to other state-of-the-art traditional and DEA solutions, in providing high- quality data series summarizations and similarity search results.

## Materials

| Paper in KDD21 | [https://qtwang.github.io/assets/pdf/kdd21-seanet.pdf](/assets/pdf/kdd21-seanet.pdf) |
| Talk at KDD21 | [https://qtwang.github.io/assets/video/kdd21-seanet.mp4](/assets/video/kdd21-seanet.mp4) |

## Codes

| SEAnet architecture | [https://github.com/qtwang/SEAnet](https://github.com/qtwang/SEAnet) |
| Indexing & query answering | [https://github.com/qtwang/isax-modularized](https://github.com/qtwang/isax-modularized) |

## Datasets

| Astro (astrophysics) | [https://swift.gsfc.nasa.gov/results/bs58mon/](https://swift.gsfc.nasa.gov/results/bs58mon/) |
| Deep1B (computer vision) | [http://sites.skoltech.ru/compvision/noimi](http://sites.skoltech.ru/compvision/noimi) |
| SALD (neuroscience) | [http://fcon_1000.projects.nitrc.org/indi/retro/sald.html](http://fcon_1000.projects.nitrc.org/indi/retro/sald.html) |
| Seismic (seismology) | [http://ds.iris.edu/data/access/](http://ds.iris.edu/data/access/) |

## Cite this work

```latex
@inproceedings{kdd21-Wang-SEAnet,
  author    = {Wang, Qitong and 
               Palpanas, Themis},
  title     = {Deep Learning Embeddings for Data Series Similarity Search},
  booktitle = {KDD'21: The 27th ACM SIGKDD Conference on Knowledge Discovery 
               and Data Mining, Virtual Event, Singapore, August 14-18, 2021},
  publisher = {ACM},
  year      = {2021},
  url       = {https://doi.org/10.1145/3447548.3467317},
  doi       = {10.1145/3447548.3467317},
  timestamp = {Thu, 05 Aug 2021 09:46:47 +0800}
}
```

<script src="https://giscus.app/client.js"
        data-repo="qtwang/qtwang.github.io"
        data-repo-id="MDEwOlJlcG9zaXRvcnkzNjgwODczOTk="
        data-category="General"
        data-category-id="DIC_kwDOFfCRZ84B-rJg"
        data-mapping="url"
        data-reactions-enabled="1"
        data-emit-metadata="0"
        data-theme="light"
        crossorigin="anonymous"
        async>
</script>
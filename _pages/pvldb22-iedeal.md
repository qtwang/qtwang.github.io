---
permalink: /pvldb22-iedeal
hidden: true
classes: wide
# layout: single-hf
# layout: single
layout: single-comments
title: "iEDeaL: A Deep Learning Framework for Detecting Highly Imbalanced Interictal Epileptiform Discharges"
author_profile: true
last_modified_at: 2023-06-18
redirect_from: 
  - /iedeal
  - /iedeal.html
  - /vldb22-iedeal
  - /vldb22-iedeal.html
  - /pvldb22-iedeal
  - /pvldb22-iedeal.html
excerpt: "PVLDB 2022"
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

[Qitong Wang](https://qtwang.github.io/) and [Themis Palpanas](http://helios.mi.parisdescartes.fr/~themisp/home.html), published in [PVLDB, Volume 16, Issue 3](https://www.vldb.org/pvldb/volumes/16/#issue-3), to be presented at [VLDB 2023](https://www.vldb.org/2023/).

## Abstract

Epilepsy is a chronic neurological disease, ranked as the second most burdensome neurological disorder worldwide. Detecting Interictal Epileptiform Discharges (IEDs) is among the most important clinician operations to support epilepsy diagnosis, rendering automatic IED detection based on electroencephalography (EEG) signals an important topic. However, most existing solutions were designed and evaluated upon artificially balanced IED datasets, which do not conform to the real-world highly imbalanced scenarios. In this work, we propose the iEDeaL framework for automatic IED detection in challenging real-world use cases. The main components of iEDeaL are the new SC neural network architecture, to efficiently detect IEDs on raw EEG series instead of extracted features, and SaSu, a novel loss function to train SC by optimizing the V -score. Experiments on two real-world imbalanced IED datasets verify the advantages of iEDeaL in offering more accurate and efficient IED detection when compared with other state-of-the-art deep learning-based and spectrogram feature-based solutions.

## Materials

| [Paper](https://www.vldb.org/pvldb/vol16/p480-wang.pdf) |

## Codes

| [Code](https://github.com/qtwang/iEDeaL) |

## Cite this work

| ACM Ref | Qitong Wang, Stephen Whitmarsh, Vincent Navarro, and Themis Palpanas. iEDeaL: A Deep Learning Framework for Detecting Highly Imbalanced Interictal Epileptiform Discharges. PVLDB, 16(3): 480 - 490, 2022. doi:10.14778/3570690.3570698 |

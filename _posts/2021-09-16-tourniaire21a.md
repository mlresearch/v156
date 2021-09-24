---
title: Attention-based Multiple Instance Learning with Mixed Supervision on the Camelyon16
  Dataset
abstract: Since the standardization of Whole Slide Images (WSIs) digitization, the
  use of deep learning methods for the analysis of histological images has shown much
  potential. However, the sheer size of WSIs is a real challenge, as they are often
  up to 100,000 pixels wide and high at the highest resolution, and therefore cannot
  be processed directly by any model. Moreover, as the manual delineation of structures
  within WSIs is tedious, histological datasets often only contain slide-level labels,
  or a limited amount of delineated slides. In this context, multiple-instance learning
  (MIL) approaches have been proposed, considering WSIs as bags of smaller images,
  designated as tiles or patches. Among these methods, the attention-based MIL aims
  at learning the importance of each tile for the slide final classification while
  at the same time performing a clustering of those tiles. In this paper, we introduce
  the concept of mixed supervision within this framework, by exploiting tile-level
  labels in addition to slide-level labels to improve the classification of slides.
  More precisely, we show on the Camelyon16 dataset that even a small proportion of
  slides with pixel-wise annotations can improve their classification but also the
  localization of tumorous regions. This improves the consistency of the results between
  the tile and slide levels and the interpretability of the algorithm.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: tourniaire21a
month: 0
tex_title: Attention-based Multiple Instance Learning with Mixed Supervision on the
  Camelyon16 Dataset
firstpage: 216
lastpage: 226
page: 216-226
order: 216
cycles: false
bibtex_author: Tourniaire, Paul and Ilie, Marius and Hofman, Paul and Ayache, Nicholas
  and Delingette, Herve
author:
- given: Paul
  family: Tourniaire
- given: Marius
  family: Ilie
- given: Paul
  family: Hofman
- given: Nicholas
  family: Ayache
- given: Herve
  family: Delingette
date: 2021-09-16
address:
container-title: Proceedings of the MICCAI Workshop on Computational Pathology
volume: '156'
genre: inproceedings
issued:
  date-parts:
  - 2021
  - 9
  - 16
pdf: https://proceedings.mlr.press/v156/tourniaire21a/tourniaire21a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---

---
title: Automated Quantification Of Blood Microvessels In Hematoxylin And Eosin Whole
  Slide Images
abstract: Tumour cells require resources to survive and proliferate. In order to be
  provided with a supportive micro-environment rich with resources to sustain optimal
  growth, tumour cells tend to reside in close proximity to a network of blood vessels.
  Quantification of blood microvessel density can be a useful measure to investigate
  the importance of resource limitation in tumours for prognostication and assigning
  treatment and mode of drug delivery. Currently, immunohistochemistry (IHC) with
  specific antibodies and the subsequent detection of its binding in the tumour tissue
  are used to identify microvessels. The automated quantification of blood microvessels
  in Hematoxylin and Eosin (H&E) stained images is not widely studied because microvessels
  are very complex and heterogeneous.  In addition, their manual identification is
  tedious, time-consuming and subjective.  We investigate whether the vasculature
  in H&E can be robustly identified in whole slide sections that would ultimately
  avoid the need for IHC and manual annotations.  We propose an artificial intelligence
  model based on Generative Adversarial Networks (GAN) that, from an input H&E image,
  can generate a synthetic Erythroblast Transformation specific related gene (ERG)
  stained image, highlighting vessel structures. We also trained a spatially constrained
  Convolutional Neural Network (CNN) to identify single cells on ERG stained whole
  slide images, and found good concordance between detected cells in synthetic and
  real ERG. This pipeline was evaluated on 2002 image patches of size 2000x2000 pixels,
  sampled from 9 whole slide images.  We achieved the mean $R^2$ of 0.70$\pm$0.14
  in our testing set.  This pipeline can pave the way to study proximity of tumour
  cells to blood vessels.  This approach has the potential to reduce the use of IHC
  and tissues and enable large quantitative studies.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: hamidinekoo21a
month: 0
tex_title: Automated Quantification Of Blood Microvessels In Hematoxylin And Eosin
  Whole Slide Images
firstpage: 94
lastpage: 104
page: 94-104
order: 94
cycles: false
bibtex_author: Hamidinekoo, Azam and Kelsey, Anna and Trahearn, Nicholas and Selfe,
  Joanna and Shipley, Janet and Yuan, Yinyin
author:
- given: Azam
  family: Hamidinekoo
- given: Anna
  family: Kelsey
- given: Nicholas
  family: Trahearn
- given: Joanna
  family: Selfe
- given: Janet
  family: Shipley
- given: Yinyin
  family: Yuan
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
pdf: https://proceedings.mlr.press/v156/hamidinekoo21a/hamidinekoo21a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---

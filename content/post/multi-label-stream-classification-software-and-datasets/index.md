---
title: Multi-label Stream Classification Software and Datasets
date: 2021-05-15T14:49:15.120Z
summary: >-
  Access HERE source code and datasets from our contribution (Cerri et al.,
  2021) presented in the 36th ACM Symposium on Applied Computing (2021).\

  In this contribution, we propose an online unsupervised incremental method based on self-organizing maps for multi-label stream classification in scenarios with infinitely delayed labels.
draft: false
featured: false
authors:
  - "-"
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
## A Self-Organizing Map for Multi-label Stream Classification

- - -

Here you can find the [source code](http://www.biomal.ufscar.br/resources/somML/Codes.zip) for the method SOM-Stream-ML, as described by [Cerri et al., 2021](https://doi.org/10.1145/3412841.3441922) (to appear). Our proposal is an online unsupervised incremental method based on self-organizing maps for multi-label stream classification in scenarios with infinitely delayed labels.\
All our implementations were performed in R. This [README](http://www.biomal.ufscar.br/resources/somML/README.txt) file describes the basic steps to execute our code.

## Datasets

- - -

Our synthetic datasets were constructed using two generatores: one provided with the [MOA framework](https://moa.cms.waikato.ac.nz/), and one provided by [Read et al., 2012](https://link.springer.com/article/10.1007/s10994-012-5279-6). We also adapted two real-world multi-label datasets provided with the [Mulan framework](http://mulan.sourceforge.net/index.html). All our datasets can be downloaded from [HERE](http://www.biomal.ufscar.br/resources/somML/Datasets.zip).

## Configuration files for the datasets

- - -

Here you can find the [configuration files](http://www.biomal.ufscar.br/resources/somML/Config.zip) that can be used to execute the Self-Organizing Maps in the provided datasets. Recall that you can use your own datasets as descrived in the [README](http://www.biomal.ufscar.br/resources/somML/README.txt) file. Just construct a corresponding configuration file.
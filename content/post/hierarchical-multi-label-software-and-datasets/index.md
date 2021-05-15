---
title: Hierarchical Multi-Label Software and Datasets
date: 2021-05-15T17:54:17.781Z
summary: >-
  Access HERE source code and datasets for the following HMC methods:


  * Hierachical Multi-label Classification with a Genetic Algorithm (HMC-GA), as described by [Cerri et al., 2019](https://www.sciencedirect.com/science/article/abs/pii/S1568494619300213)

  * Hierarchical Multi-label Classification with Neural Networks, as described by [Cerri et al., 2015](http://dx.doi.org/10.1109/ijcnn.2015.7280474) and [Cerri et al., 2016](http://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-016-1232-1)
draft: false
featured: false
authors:
  - "-"
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
---
- - -

## Genetic Algorithms

- - -

Here you can find the source code for the method HMC-GA, as described by [Cerri et al., 2019](https://www.sciencedirect.com/science/article/abs/pii/S1568494619300213). The datasets used in the paper can be downloaded [here](https://dtai.cs.kuleuven.be/clus/hmcdatasets/), from the Declarative Languages and Artificial Intelligence group ([DTAI](https://dtai.cs.kuleuven.be/) - Katholieke Universiteit Leuven), Belgium. You can also use the [Mulan](http://mulan.sourceforge.net/datasets-mlc.html) datasets for multi-label flat classification. HMC-GA suports both multi-label tasks (hierarchical and non-hierarchical).

### Hierarchical Multi-Label Classification with a Genetic Algorithm - HMC-GA

HMC-GA [source code](http://www.biomal.ufscar.br/resources/HMC_GA_New.zip) from [Cerri et al., 2019](https://www.sciencedirect.com/science/article/abs/pii/S1568494619300213)\
Example of [configuration file](http://www.biomal.ufscar.br/resources/configFileHierarchical.txt) to be used with HMC-GA for HMC classification (Funcat or GO)\
Example of [configuration file](http://www.biomal.ufscar.br/resources/configFileFlat.txt) to be used with HMC-GA for multi-label flat classification

- - -

## Neural Networks

- - -

Here you can find protein function prediction datasets for hierarchical multi-label classification with neural networks. The hierarchies of these datasets were formated to be used with the neural network-based method HMC-LMLP, as described by [Cerri et al., 2015](http://dx.doi.org/10.1109/ijcnn.2015.7280474) and [Cerri et al., 2016](http://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-016-1232-1). The original datasets can be downloaded [here](https://dtai.cs.kuleuven.be/clus/hmcdatasets/), from the Declarative Languages and Artificial Intelligence group ([DTAI](https://dtai.cs.kuleuven.be/) - Katholieke Universiteit Leuven), Belgium.

### Funcat Datasets (Tree Structure) to be used with HMC-LMLP

[Cellcycle](https://sites.google.com/site/cerrirc2/files/CellCycle_FUN.zip?attredirects=0) | [Church](https://sites.google.com/site/cerrirc2/files/Church_FUN.zip?attredirects=0) | [Derisi](https://sites.google.com/site/cerrirc2/files/Derisi_FUN.zip?attredirects=0) | [Eisen](https://sites.google.com/site/cerrirc2/files/Eisen_FUN.zip?attredirects=0) | [Gasch1](https://sites.google.com/site/cerrirc2/files/Gasch1_FUN.zip?attredirects=0) | [Gasch2](https://sites.google.com/site/cerrirc2/files/Gasch2_FUN.zip?attredirects=0) | [Pheno](https://sites.google.com/site/cerrirc2/files/Pheno_FUN.zip?attredirects=0) | [Spo](https://sites.google.com/site/cerrirc2/files/SPO_FUN.zip?attredirects=0) | [Expr](https://sites.google.com/site/cerrirc2/files/Expr_FUN.zip?attredirects=0) | [Seq](https://sites.google.com/site/cerrirc2/files/Seq_FUN.zip?attredirects=0)

### Gene Ontology Datasets (DAG Structure) to be used with HMC-LMLP

[Cellcycle](https://sites.google.com/site/cerrirc2/files/Cellcycle_GO.zip?attredirects=0&d=1) | [Church](https://sites.google.com/site/cerrirc2/files/Church_GO.zip?attredirects=0&d=1) | [Derisi](https://sites.google.com/site/cerrirc2/files/Derisi_GO.zip?attredirects=0&d=1) | [Eisen](https://sites.google.com/site/cerrirc2/files/Eisen_GO.zip?attredirects=0&d=1) | [Gasch1](https://sites.google.com/site/cerrirc2/files/Gasch1_GO.zip?attredirects=0&d=1) | [Gasch2](https://sites.google.com/site/cerrirc2/files/Gasch2_GO.zip?attredirects=0&d=1) | [Pheno](https://sites.google.com/site/cerrirc2/files/Pheno_GO.zip?attredirects=0&d=1) | [Spo](https://sites.google.com/site/cerrirc2/files/Spo_GO.zip?attredirects=0&d=1) | [Expr](https://sites.google.com/site/cerrirc2/files/Expr_GO.zip?attredirects=0&d=1) | [Seq](https://sites.google.com/site/cerrirc2/files/Seq_GO.zip?attredirects=0&d=1)

### Hierarchical Multi-Label Classification with Local Multi-Layer Perceptron - HMC-LMLP

HMC-LMLP-Predicted [source code](https://sites.google.com/site/cerrirc2/files/HMC_LMLP_Predicted.zip?attredirects=0) from [Cerri et al., 2016](http://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-016-1232-1)\
Example of [configuration file](https://sites.google.com/site/cerrirc2/files/configHMC_LMLP_Predicted.txt?attredirects=0) to be used with HMC-LMLP-Predicted (Funcat)\
Example of [configuration file](https://sites.google.com/site/cerrirc2/files/configHMC_LMLP_GO.txt?attredirects=0&d=1) to be used with HMC-LMLP-Predicted (Gene Ontology)
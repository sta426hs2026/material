
# Statistical Analysis of High-Throughput Genomic and Transcriptomic Data
Fall/Herbst-semester 2026

## Lectures
Mondays 9.00-9.45 (Y27-H-46), 10.00-10.45 (Y27-H-46)

## Exercises
Monday 11.00-11.45

## Lecturers

[Dr. Hubert Rehrauer](http://www.fgcz.ch/the-center/people/rehrauer.html), Group Leader of Genome Informatics at [FGCZ](http://www.fgcz.ch/)

[Prof. Dr. Mark Robinson](https://robinsonlabuzh.github.io/), Professor of Statistical Genomics, [DMLS](https://www.mls.uzh.ch/en.html), UZH

[Dr. Pierre-Luc Germain](https://hest.ethz.ch/en/department/people/organisational-units/institute-for-neuroscience/molecular-and-behavioral-neuroscience/persdetail.MjUwODk0.TGlzdC8yOTE3LDM2MjU2OTk1OA==.html), Lecturer, [Department of Health Sciences and Technology](https://hest.ethz.ch/en), ETHZ

## Schedule

| Date  | Lecturer | Topic | Exercise | JC1 | JC2 |
| --- | --- | --- | --- | --- | --- |
| 14.09.2026  | Mark+Hubert | admin; mol. bio. basics | quarto; git(hub) | | |
| 21.09.2026  | Hubert | NGS intro; exploratory data analysis | EDA in R | | |
| 28.09.2026  | Hubert | mapping  | Rsubread | | |
| 05.10.2026  | Mark  | limma + friends | linear model simulation + design matrices | | |
| 12.10.2026  | Hubert | RNA-seq quantification | RSEM  | | | 
| 19.10.2026  | Mark | hands-on session #1: benchmarking | exercise: Omnibenchmark | [Data-driven hypothesis weighting increases detection power in genome-scale multiple testing](https://pubmed.ncbi.nlm.nih.gov/27240256/) (SS,FO) | X |
| 26.10.2026  | Mark | edgeR+friends 1 | basic edgeR/voom | [scMultiMap: Cell-type-specific mapping of enhancers and target genes from single-cell multimodal data](https://pubmed.ncbi.nlm.nih.gov/40287418/) (MS, TP) | [Differential abundance testing on single-cell data using K-nearest neighbour graphs](https://pmc.ncbi.nlm.nih.gov/articles/PMC7617075/) (AW, BG, MM) |
| 02.11.2026  | Mark | edgeR+friends 2 | advanced edgeR/voom | [Probabilistic cell-type assignment of single-cell RNA-seq for tumor microenvironment profiling](https://www.nature.com/articles/s41592-019-0529-1#Sec2) (AM, SP) | [JUNIPER: Reconstructing Transmission Events from Next-Generation Sequencing Data at Scale](https://pmc.ncbi.nlm.nih.gov/articles/PMC11975037/) (YS, OC, SK) |
| 09.11.2026  | Mark | hands-on session #2: RNA-seq |  FASTQC/Salmon/etc. | [Sensitive cluster-free differential expression testing](https://www.biorxiv.org/content/10.1101/2023.03.08.531744v1) (LPD, ES, JS) | [Normalization and variance stabilization of single-cell RNA-seq data using regularized negative binomial regression](https://doi.org/10.1186/s13059-019-1874-1) (BR, LT, ZD) |
| 16.11.2026  | Hubert | single-cell 1: preprocessing, dim. red., clustering | clustering | [Spatial transcriptomics at subspot resolution with BayesSpace](https://www.nature.com/articles/s41587-021-00935-2) (NM, AM) | [spicyR: spatial analysis of in situ cytometry data in R](https://academic.oup.com/bioinformatics/article/38/11/3099/6570585) (IG, MFB) |
| 23.11.2026  | Mark | single-cell 2: clustering, marker gene DE | marker gene DE | [Model-based dimensionality reduction for single-cell RNA-seq using generalized bilinear models](https://academic.oup.com/biostatistics/article/26/1/kxaf024/8229239) (SP, AR, BU) | [A phylogenetic method to perform genome-wide association studies in microbes that accounts for population structure and recombination](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005958) (SH, CM) |
| 30.11.2026  | Pierre-Luc | hands-on session #3: single-cell RNA-seq | full scRNA-seq pipeline | [Efficient differential expression analysis of large-scale single-cell transcriptomics data using Dreamlet](https://www.nature.com/articles/s41467-026-75680-8) (GK, WR) | [LinDA: linear models for differential abundance analysis of microbiome compositional data](https://pmc.ncbi.nlm.nih.gov/articles/PMC9012043/#Abs1) (KD, JT) |
| 07.12.2026  | Mark | spatial omics 1 | spatial statistics | [A Bayesian framework for longitudinal EHR and genetic discovery](https://doi.org/10.1038/s41586-026-10780-5) (AG, LB) | [Deep generative modeling for single-cell transcriptomics](https://www.nature.com/articles/s41592-018-0229-2) (MG) |
| 14.12.2026  | Mark | spatial omics 2 | structures, DSP | [Dream: powerful differential expression analysis for repeated measures designs](https://academic.oup.com/bioinformatics/article/37/2/192/5878955) (SS, EG) | X |


## Course material

Assuming you have git installed locally, you can check out the entire set of course materials with the following command (from command line):
```
git clone https://github.com/sta426hs2026/material.git
```
and get updates by running `git pull` at any later time in the same directory.

Alternatively, to retrieve a ZIP file of the repository, you can click on the (green) 'Code' button (top right of main panel) and then click 'Download ZIP'.


This repository contains two independent projects focused on understanding cellular processes at different biological scales:

1. Hi-C Data Analysis (interacting_regions.ipynb):

Investigates the spatial organization of DNA in IMR90 (fibroblast) cells.
Aims to understand the relationship between chromatin interactions and gene expression.

2. Single-Cell RNA-seq Data Analysis (rna_seq.ipynb):

Explores the structure and patterns within high-dimensional single-cell RNA-seq data.
Seeks to identify cell clusters and potential marker genes.

Data
Hi-C data: Tab-separated value files representing chromosome interactions (see interacting_regions.ipynb for details).
Single-cell RNA-seq data: CSV file containing normalized transcript compatibility counts (TCC) for each cell and gene (see rna_seq.ipynb for details).

These files reference hic_part1, hic_part2, and trapnell.csv. Due to the size of these datasets, I chose not to include them on the repo

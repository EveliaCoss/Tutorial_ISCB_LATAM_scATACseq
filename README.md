<img src="https://www.wellcomeconnectingscience.org/wp-content/themes/new_wellcome_connecting_science/dist/assets/svg/logo.svg" alt="WCS Logo" width="150" style="float: left;">
<img src="https://github.com/EveliaCoss/Tutorial_ISCB_LATAM_scATACseq/blob/main/Logo_JAGUAR.png?raw=true" alt="WCS Logo" width="30" style="float: right;">

# Tutorial scATACseq 

Single Cell Genomic Approaches to Study the Immune System - Latin America - the Caribbean 

9–11 November 2024 Universidad CES, Medellín, Colombia

## About the course 📌

Speakers:

- **Diego Ramirez** - Bachelor in Genomic Sciences, Escuela Nacional de Estudios Superiores Unidad Juriquilla UNAM (ENES Juriquilla), Mexico.
- **Evelia Lorena Coss-Navarrete** - PostDoc, International Laboratory for Human Genome Research (LIIGH)-UNAM, Mexico.

## Inscription

https://coursesandconferences.wellcomeconnectingscience.org/event/single-cell-genomic-approaches-to-study-the-immune-system-latin-america-the-caribbean-20241109/

### Abstract:

Single-cell transposase-accessible chromatin sequencing (scATAC-seq) represents the most innovative technology for examining genome-wide regulatory landscapes in single cells. For this tutorial, we will be analyzing a single-cell ATAC-seq dataset of human peripheral blood mononuclear cells (PBMCs) provided by 10x Genomics. We will run bridge integration for PBMC with the newly released Azimuth ATAC workflow. In this workshop we will review the existing statistical tools for analyzing scATAC-seq data, how to document your analysis and review some tools for interpreting results.

### Learning objectives:

1.   Fundamentals of Single Cell ATAC-seq (scATAC-seq) and Multiome analysis.
2.   Single-Cell ATAC-seq Pre-Processing and Quality Control.
3.   Loading in and pre-processing the scATAC-seq, multiome, and scRNA-seq reference datasets.
4. Mapping the scATAC-seq dataset via bridge integration.
5. Exploring and assessing the resulting annotations.
6. Motif analysis with Signac

### About datasets

In this tutorial, we go over how to use scvi-tools functionality in R for analyzing ATAC-seq data. We will closely follow the PBMC tutorial from [Signac](https://satijalab.org/signac/articles/pbmc_vignette.html), using scvi-tools when appropriate. In particular, we will

1. Use PeakVI for dimensionality reduction and differential accessiblity for the ATAC-seq data
2. Use scVI to integrate the unpaired ATAC-seq dataset with a match scRNA-seq dataset of PBMCs

This tutorial requires Reticulate. Please check out our installation [guide](https://www.scvi-tools.org/en/latest/installation.html#scvi-tools-installation-for-R) for instructions on installing Reticulate and scvi-tools.


https://colab.research.google.com/drive/1hyLIYmhj792nk_xOLGoYDHZjXd-TeueZ?usp=sharing


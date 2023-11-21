# Explore all projects 

## Contents

## Project 1. Integrating single-cell Hi-C and single-cell RNA sequencing data
**Leading Lab:** Noble Lab

**Stakeholders:** Anupama Jha (anupamaj [ a t ] uw.edu) and Gang Li (gangliuw [ a t ] uw.edu)

**Desired deliverable:** Benchmarking results comparing multiple existing software tools for integrating scHiC and scRNA data.

**Expected coding experience level:** Intermediate-Advanced.

**Abstract:** Recently, Liu et al. developed HiRES, a multi-omics sequencing approach to simultaneously profile 3D chromatin contacts and gene expression in single cells. The HiRES assay thus directly links chromatin conformation and gene expression profiles within single cells. Previous studies that aimed to investigate the interplay between chromatin interactions and transcriptomic profiles necessarily generated unpaired single-cell RNA-sequencing and chromatin conformation data. For the hackathon, we will use the newly available HiRES data to benchmark existing software tools developed for matching cells across modalities. In particular, we evaluate GLUE, LS-MMDMA (Meng 2023), Pomona (Cao 2021), SCOT (Demetci 2022), Synmatch (Hristov 2022), and CMOT (Alatkar 2023). In addition, we will consider four different techniques for representing the scHi-C contact matrices, including the contact decay profile, the HiCRep (Lin 2021) similarity score, a latent Dirichlet allocation model (Kim 2020), and the scGAD method (Shen 2022). Our results will compare and contrast the performance of these tools and Hi-C representation techniques in the context of integration with scRNA-seq data. For the hackathon, we will use co-assay data to validate integration of scRNA-seq and scHi-C.
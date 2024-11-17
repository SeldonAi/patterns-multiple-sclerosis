# # Analysis of Gene Expression Patterns in Multiple Sclerosis
This project was conducted as part of the Master's degree in Computer Science at the University of Pisa, under the course "Computation Health Laboratory" (755AA) by Prof. Corrado Priami for the academic year 2023-2024.

## Team Members
- Gabriele Benanti - g.benanti@studenti.unipi.it - Roll number: 550552
- Giulia Ghisolfi - g.ghisolfi@studenti.unipi.it - Roll number: 664222
- Alessandro Stefanelli - a.stefanelli3@studenti.unipi.it - Roll number: 686084

## Project Overview
This project focuses on the differential expression analysis in multiple sclerosis (MS) patients compared to healthy controls. We investigate these expression differences in peripheral blood mononuclear cells (PBMCs) and cerebrospinal fluid cells (CSFs), with a focus on various cell types including T cells, B cells, Monocytes, Plasma cells, and Innate Lymphoid Cells (ILC).

## Methodology
Our analysis integrates data from different studies and datasets to explore gene expression patterns that distinguish MS patients from healthy controls. Key methodologies include:
- Differential expression analysis
- Data integration from multiple sources
- Biomarker identification

# MS-GEO-Datasets: Multiple Sclerosis Datasets from GEO

This repository hosts datasets obtained from the Gene Expression Omnibus (GEO) related to multiple sclerosis (MS) research. 

## Datasets Overview

| GEO Accession | Provided Information | Technology Used | Type of Data | Tissue/Cell Type Analyzed | Specific Samples |
|---------------|----------------------|------------------|--------------|----------------------------|------------------|
| [GSE239626](GSE239626/README.md) | Gene expression profiling using high-throughput sequencing (scRNA-seq and CITE-seq) | scRNA-seq, CITE-seq | Processed matrix (gene expression) | Peripheral blood mononuclear cells (PBMCs) | Multiple sclerosis patients treated with high-dose vitamin D and placebo |
| [GSE159033](GSE159033/README.md) \| [GSE159035](GSE159035/README.md) | Whole-transcriptome profiling in PBMCs from patients with LS-OCMB characterization reveals 2 linear RNAs and 2 circular RNAs as biomarkers of highly active disease | Non-coding RNA profiling by array, RNA-seq | Processed data (miRNA), Processed data (linear RNAs, circRNAs) | Peripheral blood mononuclear cells (PBMCs) | Multiple sclerosis patients with positive and negative LS-OCMB status |
| [GSE173787](GSE173787/README.md) | Identification of key pathways dysregulated in multiple sclerosis lesions using transcriptome profiling | Microarray, RNA-seq | Raw and processed data (gene expression) | Brain tissue (lesions), B cells type | Multiple sclerosis patients with active lesions. |
| [GSE194078](GSE194078/README.md) | AXL+SIGLEC6+ dendritic cells in cerebrospinal fluid and brain tissues of patients with autoimmune inflammatory demyelinating disease of CNS | Expression profiling by high throughput sequencing | Single cell transcriptomics | Cerebrospinal fluid and peripheral blood mononuclear cells (PBMCs) | 9 Inflammatory demyelinating disease patients and 2 healthy controls without inflammatory disease of the central nervous system |
| [GSE138266](GSE138266/README.md) | Integrated single cell analysis of blood and cerebrospinal fluid leukocytes in multiple sclerosis | Expression profiling by high throughput sequencing | Single cell transcriptomics | Blood and cerebrospinal fluid leukocytes | 5 MS patients vs. 5 healthy controls |
| [GSE144744](GSE144744/README.md) | Identifying CNS-colonizing T cells as potential therapeutic targets to prevent progression of multiple sclerosis | Expression profiling by high throughput sequencing | Processed data (single-cell transcriptomes, surface protein profiles) | Peripheral blood mononuclear cells (PBMCs), brain tissue (post-mortem) | Multiple sclerosis patients (RRMS, PPMS) and healthy controls |

## Accessing the Data
The data for each study can be accessed through the provided links to their respective README files, which contain detailed information and links to the GEO platform.

## Acknowledgements
We thank Prof. Corrado Priami for his guidance and support throughout this project, as well as our peers for their valuable insights.


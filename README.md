Integrated Multi-Omics Analysis

This repository contains notebooks for integrating and analyzing multi-omics data, specifically focusing on RNA-seq, ATAC-seq, and spatial transcriptomics datasets. The integration is performed using advanced computational methods to provide a comprehensive view of gene expression, chromatin accessibility, and spatial localization. The key steps and methods used across the notebooks are:

- Melanoma Study using Perturb-CITE-Seq
  - A combined therapeutic approach targeting COL1A1 and EIF4A for melanoma treatment.
  - A multi-targeted strategy for aggressive melanoma, combining PRAME-targeted immunotherapy with PARP inhibitors and EMT/stemness pathway inhibitors.
  - The complex interplay between CD274 (PD-L1), CD58, and CD9 in different immune microenvironments.
  - The potential role of LY96 in immune evasion across multiple cancer types, including melanoma.
- RNA-ATAC Integration with scVI
  - Integrated RNA-seq and ATAC-seq datasets using scVI to analyze gene expression and chromatin accessibility data.
  - Leveraged publicly available datasets for a comprehensive analysis.
- RNA-ATAC Integration with FGW and Random Forest
  - Utilized the Fused Gromov-Wasserstein (FGW) algorithm to align RNA-seq and ATAC-seq data.
  - Quantified the integration using FOSCTTM, Jensen-Shannon Divergence, and cross-entropy metrics.
  - Used a Random Forest model to transfer labels between datasets.
- in silico gene perturbation analysis using the CellOracle package
  - Performed pseudotime analysis to order cells along a developmental trajectory
  - Analyzed the effects of gene knockouts on downstream gene expression using gene regulatory networks 
- Spatial Mapping using Tangram Package
  - Mapped RNA-seq data onto spatial coordinates using a stereo-seq dataset with the Tangram package.
  - Analyzed cell-cell interactions at different developmental stages, enhancing the understanding of spatial gene expression patterns.
  - Integration of RNA-seq with Spatial Transcriptomics
  - Integrated RNA-seq data with spatial transcriptomics (stereo-seq) to map gene expression onto spatial coordinates.
  - Facilitated label transfer, analysis of cell-cell communication through ligand-receptor interactions, and investigation of cell-cell transitions using manually curated zebrafish genes for proliferation and apoptosis.
- Differential Expression Analysis of Immune-Related Genes
  - Conducted differential expression analysis of immune-related genes in zebrafish across developmental stages.
  - Examined genes related to viral diseases, bacterial infections, and stress responses.

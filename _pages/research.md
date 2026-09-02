---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research lies at the intersection of **statistical genetics, Mediation Analysis, and biomedical data science**. I develop statistical and machine learning methods for complex biomedical data, with the goal of improving reliable discovery, genetic risk prediction, and biological interpretation.

Research Areas
======

### Statistical Genetics and Genomics

I am interested in developing statistical methods that connect genetic association signals with disease-related genes and biological mechanisms. My work includes polygenic risk prediction, transcriptome-wide association studies, trans-regulatory gene mapping, and the integration of genetic and functional genomic information.

A recent focus of this work is the development of statistical genetic approaches for prioritizing disease-driving genes and pathways.


These methods have been applied to genetic, genomic, and epigenetic studies.

### Mediation Analysis

I develop statistical methods for identifying potential mediating mechanisms in high-dimensional biomedical data.

My work has focused particularly on high-dimensional mediation analysis with survival outcomes, including methods that provide finite-sample false discovery rate control.

### Polygenic Risk Prediction

I am interested in improving the transferability of polygenic risk scores across populations.

My previous work has explored transfer learning approaches that leverage information from large-scale genome-wide association studies to improve genetic risk prediction in populations with relatively limited sample sizes.

### Biomedical and Clinical Data Science

My research also extends to large-scale clinical and electronic health record data.

I am interested in:

- Longitudinal electronic health record modeling
- Clinical risk prediction
- Machine learning for patient trajectories
- Cross-modal biomedical representation learning
- Integration of structured clinical and omics data


Selected Research
======

### Trans-regulatory Gene Mapping in Asthma

Our recent work develops a trans-regulatory gene mapping framework for prioritizing disease-driving genes in asthma.

By integrating statistical genetics, trans-regulatory information, rare-variant analysis, and functional validation, this work aims to move from statistical genetic associations toward biologically interpretable disease mechanisms.

**Salamone, I. M., Tian, P.*, Qi, Z., et al.**  
*Trans-regulatory gene mapping prioritizes disease drivers in asthma.*  
**Cell**, 2026.

### High-dimensional Mediation Analysis

I have developed statistical methods for high-dimensional mediation analysis with survival outcomes, including **CoxMKF** and **CoxMDS**.

These methods focus on reliable mediator identification while controlling false discoveries in high-dimensional biomedical applications.

### Statistical Genetics and Risk Prediction

My work also includes methods for transcriptome-wide association studies and multiethnic polygenic risk prediction, including **TWAS-GKF** and transfer-learning approaches for genetic risk prediction across diverse populations.


Research Software
======

I develop open-source statistical software for high-dimensional inference, statistical genetics, and biomedical data analysis.

### DANDELION

**DANDELION** is a statistical genetics framework for trans-regulatory gene mapping and disease-gene prioritization. It integrates trans-regulatory information with genetic association evidence to identify genes that are more closely connected to disease mechanisms.

The framework was developed and applied in our recent study of asthma genetics published in *Cell*.

[**View DANDELION on GitHub →**](https://github.com/mxxptian/DANDELION)


### Grace-AKO

**Grace-AKO** is a knockoff-based variable selection method designed for high-dimensional genomic data. It incorporates prior gene-network structures into variable selection and uses aggregated knockoff inference to improve selection stability while controlling the false discovery rate.

[**View Grace-AKO on GitHub →**](https://github.com/mxxptian/GraceAKO)


### TL-Multi

**TL-Multi** is a transfer-learning framework for multiethnic polygenic risk prediction. It leverages information from large-scale GWAS in well-represented populations to improve genetic risk prediction in populations with more limited training data.

[**View TL-Multi on GitHub →**](https://github.com/mxxptian/TLMulti)

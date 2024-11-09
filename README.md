# Biomarker-Analysis---Lung-Cancer
Overview

This repository contains code, data, and resources for analyzing biomarkers associated with lung cancer. We aim to identify key biomarkers that can aid in early detection, prognosis, and personalized treatment strategies for lung cancer patients. The analysis focuses on statistical, bioinformatics, and machine learning techniques to process and interpret biomarker data.

Background

Biomarkers are biological indicators, often detectable in blood or tissue samples, that can indicate the presence or progression of diseases. For lung cancer, identifying reliable biomarkers is crucial for improving diagnostic accuracy, determining prognosis, and guiding treatment decisions. This repository explores potential biomarkers using multi-omics data, including genomics, transcriptomics, and proteomics.

Data Sources

Data sources used in this repository include:

Public Databases: Such as GEO (Gene Expression Omnibus).

Clinical Data: Includes information on patient demographics, treatment history, and survival outcomes.

Genomics Data: Gene concept that pulls together multiple sources of functional annotations downloaded from DAVID (the Database for Annotation, Visualization, and Integrated Discovery)


Analysis Techniques

1. Fold Change and p-value Calculations: Calculated fold change in Excel to identify upregulated and downregulated genes, and used p-values for statistical significance, isolating genes with significant expression differences.
2. Significance Filtering and Clinical Trials Check: Filtered significant genes and cross-referenced them with ClinicalTrials.gov to verify clinical relevance to lung cancer.
3. Data Visualization in Tableau: Tableau was used to create visualizations of gene expression patterns and significant genes with clinical relevance, enhancing data interpretation.

RESULTS

The top genes with significant expression changes (high positive fold change and low p-values) that could serve as potential biomarkers are:

RPS6 (Fold Change: 5.0, P-value: 0.00010) – As a ribosomal protein, it plays a central role in protein synthesis, and its high expression suggests involvement in cellular growth or response processes.

CD74 (Fold Change: 4.5, P-value: 0.02300) – An MHC class II chaperone, involved in the immune response. Its strong expression indicates a potential immune response or inflammatory marker.

FN1 (Fold Change: 4.0, P-value: 0.00001) – Involved in cell adhesion, suggesting it may play a role in structural or metastatic processes.








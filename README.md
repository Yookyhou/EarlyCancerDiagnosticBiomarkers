# Design of Early Cancer Diagnosis Markers and Understanding of Their Evolution Mechanisms

Cancer is a disease associated with genetic variations. In many cases, patients are already in the mid to late stages of the disease at the time of diagnosis, missing the optimal treatment window. Therefore, developing diagnostic markers aimed at early cancer detection has long been one of the main challenges in clinical medicine.

Current cancer diagnosis and pathological staging mainly rely on tumor size, whether the tumor has metastasized, the patient's biochemical indicators, clinical pathological image analysis, and other means. These methods are highly dependent on the accuracy of the tests and the clinical experience of the doctors. According to the central dogma of biology, genes are the fundamental factors that determine phenotypic changes. Changes in a patient's tumor status, biochemical indicators, or pathological image abnormalities often occur later than abnormalities in gene data. Therefore, analyzing gene data may allow for earlier cancer detection, providing new ideas for early diagnosis and deeper insights into the mechanisms of cancer development.

Gene expression data is a common type of gene-related data that reflects the abundance of gene transcription products (such as messenger RNA, mRNA) in cells. This data can be used to analyze which genes' expressions change under different conditions, how gene activity is influenced by external conditions, and the co-expression relationships between genes. This data plays an important role in the design of clinical diagnostic markers and understanding the mechanisms of cancer occurrence and development.

## Problem Description

Based on the data provided in the title, please answer the following questions:

1. **Early vs. Late Stage Cancer**: Which genes show significant expression changes in early and late stages? How are these genes related to each other?
2. **Diagnostic Marker Design**: Which genes or relationships between genes can serve as diagnostic markers to determine or analyze the patient's pathological status? Please provide specific quantitative indicators or feature sets, and evaluate the recognition accuracy of the designed diagnostic markers, especially for early cancer diagnosis.
3. **Heterogeneity Handling**: How can the impact of heterogeneity between different patients be minimized during the analysis process?

## Terminology

- **Gene Expression Data**: The abundance of gene transcription products in cells, describing the current active state of genes.
- **Biomarkers (Diagnostic Markers)**: Features used to determine the patient's pathological status, which can be the expression values of one or several genes or quantitative values of gene expression relationships. Biomarkers are typically better when they are more concise to save testing costs.
- **Heterogeneity**: Describes the degree of variation between data. Even if patients are in the same pathological stage, there may be significant differences in gene expression data, biochemical indicators, and medical imaging data, posing challenges for data analysis.

## Data File Description

- **Normal_exp.csv**: Gene expression data from normal individuals
- **EarlyStage_exp.csv**: Gene expression data from early-stage patients
- **LaterStage_exp.csv**: Gene expression data from late-stage patients

**Data Format**:  
- The first row is the header, containing sample IDs for each patient (except the first column).
- The first column contains gene names, and columns two through the last column contain the gene expression values for each patient.

## References

1. [Gene Expression Profile Analysis (MathWorks)](https://ww2.mathworks.cn/help/bioinfo/ug/gene-expression-profile-analysis.html?requestedDomain=cn)
2. Langfelder, P., & Horvath, S. WGCNA: an R package for weighted correlation network analysis. *BMC Bioinformatics*, 9, 559 (2008). [https://doi.org/10.1186/1471-2105-9-559](https://doi.org/10.1186/1471-2105-9-559)

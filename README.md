## Background

Gene Set Enrichment Analysis (GSEA) is a computational method that determines whether an a priori defined set of genes shows statistically significant, concordant differences between two biological states
(e.g. phenotypes). 

For example, GSEA can be performed on a normalized RNA-seq dataset to determine the most significant differentially expressed genes between an HIV RNA-seq sample vs Healthy RNA-seq sample. This is a powerful method to associate a disease phenotype to a group of genes/proteins. GSEA attributes a specific weight to each gene/protein in the input list that depends on a metric of choice, which is usually represented by quantitative expression data.

## About

I performed a GSEA analysis of treatment effect differences in low- and high-fibrosis Hepatitis C patients. 

To view results:
1. ```$ cd output```
2. Select a comparison category
3. Open the ```index.html``` file. This contains all the plots and tabular data

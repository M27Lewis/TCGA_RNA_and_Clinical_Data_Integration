# TCGA_RNA_and_Clinical_Data_Integration
This is a repo where I take TCGA RNA-Seq data and multiple clinical data sheets and clean/reformat these data to integrate genomics and clinical data for some toy analysis
Files:
1) BRCA_TCGA_RNA_Analysis.Rmd
   Markdown file where the analysis was performed, most of this was done using tidyverse notation with some base R mixed in. This analysis is based around determining if a handful of genes are enriched for expression in specific suptypes or based on hormone status. This requires a few datasets such as TCGA RNA-Seq data (post normalization from firehose) and various clinical data sheets. 
2) BRCA_TCGA_RNA_Analysis.html
   The html representation of the analysis 

# Candida glabrata CBS138 and BG2 differential gene expression

data/ -- contains all input and output data, including

- data/featureCounts/ - gene counts, not normalised, produced by the pre-processing pipeline
- data/DESeq2/ - upregulated and downregulated genes for different comparisons identified by DESeq2
- data/reciprocal_blast/ - results of Reciprocal Blast Best Hits (RBBH) analysis between _C. glabrata_ CBS138 and _S. cerevisiae_ as well as between _C. glabrata_ CBS138 and BG2.
- data/sample_sheets/ - sample sheet connecting stain name and growth condition and RNAseq sample ID

rmd/ -- R and Python scripts for data analysis written as R Markdown files

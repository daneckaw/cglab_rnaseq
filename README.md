# cglab_rnaseq - Candida glabrata CBS138 and BG2 differential gene expression in response to azole drugs

This repository contains RNA-seq data and analysis, accompanying the manuscript:

> Antifungal exposure can enhance Candida glabrata pathogenesis
> Gabriela Fior Ribeiro, Weronika Danecka, Logan Tomlinson, Edward W.J. Wallace, Delma S Childers
> (to be posted on bioRxiv)

The analysis was done by Weronika Danecka and Edward Wallace, questions to Edward.Wallace@ed.ac.uk.

The RNA-seq data and experimental metadata are available on Gene Expression Omnibus (GEO), accession number [GSE273379](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE273379).


# Contents

## data/

Contains all input and output data, including

- data/bedgraph - bedgraph plots for genome browser visualisation
- data/featureCounts/ - gene counts, not normalised, produced by the pre-processing pipeline
- data/reciprocal_blast/ - results of Reciprocal Blast Best Hits (RBBH) analysis between _C. glabrata_ CBS138 and _S. cerevisiae_ as well as between _C. glabrata_ CBS138 and BG2.
- data/sample_sheets/ - sample sheet connecting strain name, growth condition, and RNAseq sample ID
- data/DESeq2/ - upregulated and downregulated genes for different comparisons identified by DESeq2
- data/GO/ - Gene Ontology analysis of deseq2 results.


## rmd/ 

R (and some Python) scripts covering all data analysis, written as R Markdown files.

## figures/

Figures output by Cglabrata_RNAseq_QC_DGE.Rmd, to use in manuscript.

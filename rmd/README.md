# rmd/

R (and some Python) scripts covering all data analysis, written as R Markdown files.

Cglabrata_RNAseq_QC_DGE.Rmd contains most of the data analysis, including quality control (correlation plots, PCA, etc.), and differential gene expression analysis with DESeq2.
This file produces all the RNA-seq related figures used for the manuscript and supplement, and several others.
An earlier version of file ran both featureCounts_preprocess.Rmd and ortho_preprocess.Rmd.

featureCounts_preprocess.Rmd changes the formatting of featureCounts output for individual sequencing samples to one compatible with DESeq2.

ortho_preprocess.Rmd generates gene pairs from Reciprocal Blast Best Hits output and, in the future, from orthofinder output.

rpm_visualiser.Rmd is an interactive application for viewing normalized gene expression (rm, reads per million) by gene, using the shiny package.

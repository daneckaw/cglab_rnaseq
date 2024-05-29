new_dge_cglabrata.Rmd runs both featureCounts_preprocess.Rmd and ortho_preprocess.Rmd.
featureCounts_preprocess.Rmd changes the formatting of featureCounts output for individual sequencing samples to one compatible with DESeq2.
ortho_preprocess.Rmd generates gene pairs from Reciprocal Blast Best Hits output and, in the future, from othofinder output.

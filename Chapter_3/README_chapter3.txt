Given the large size of all datasets at hand, scripts were run in the following order to download data in sections:

1) Download_first_half.Rmd
2) Download_second_half.Rmd

The above two scripts download all RNAseq data from the TCGA in STAR Counts form. Then:

3) LAG3_ligands_across_datasets.Rmd

This third script necessitates two have the data from the first two scripts loaded in. It then
generates figures assessing the expression of LAG-3 ligands across tumour types. Finally@

4) Chapter3_all_other_figures.Rmd

Is run to perform the rest of the analysis outlined in the chapter for 
COAD and BRCA datasets
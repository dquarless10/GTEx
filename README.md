# GTEx
This repository contains R scripts to query GTEx results.

## Data
GTEx_Analysis_V6_eQTLs.tar.gz

Example dataset is the first 100 lines of the whole blood results

head -n100 Whole_Blood_Analysis.snpgenes > Whole_Blood_Analysis.snpgenes.head100

## Code
geneGrep function takes GTEx results and gene list as arguments, returns GTEx eSNP results for genes in gene list. Genes without significant eSNPs are removed from results.

Code also shows example.

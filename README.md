# GLDS-289
Analyses of GLDS-289 Impact of spaceflight on gene expression in the thymus
https://genelab-data.ndc.nasa.gov/genelab/search_studies/?q=glds-289&data_source=cgene

Run notebooks in this order:
(1) GLDS-289 rRNA no rRNA compare.ipynb
(2) Compare DESeq2 results.ipynb

Will generate 3 csv files comparing DEGs with and without rRNA using three cutoffs (padj < 0.01; padj < 0.1, lfc > 0.1; padj <0.05)

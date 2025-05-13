# EnrichSci_analysis

This repository contains analysis notebooks and monocle CellDataSet objects from EnrichSci profiling of young and aged mouse brain oligodendroytes.

## Usage
Notebooks contain key downstream analyses used in the EnrichSci paper. Key Monocle CellDataSet objects are provided on Zenodo at DOI .

OL_DE_analysis.ipynb performs DE analysis to identify and plot DE genes and exons for oligodendrocyte subtypes MOL2 and MOL5/6.
cds_olg_gene_exon.rds, which contains both gene and exon counts, is used in this notebook.

OL_density_plots.ipynb utilizes a modified miloR pipeline to generate cell neighborhoods, classify them as non-enriched, young-enriched, or aged-enriched, and plot the density of these neighborhoods.
cds_olg.rds, which contains only gene counts, is used in this notebook.

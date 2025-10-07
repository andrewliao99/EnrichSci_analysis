# EnrichSci_analysis

This repository contains notebooks for analysis of young and aged mouse brain oligodendrocytes profiled via EnrichSci.

## Usage
Notebooks contain key downstream analyses used in the EnrichSci paper. Key Monocle CellDataSet objects are provided on Zenodo at 10.5281/zenodo.15393823. Additional CellDataSet objects from the cell line mixture experiments are also provided.

OL_density_plotting.ipynb utilizes a modified miloR pipeline to generate cell neighborhoods, classify them as non-enriched, young-enriched, or aged-enriched, and plot the density of these neighborhoods.
cds_olg.rds, which contains only gene counts, is used in this notebook.

OL_DE_analyses.ipynb performs DE analysis to identify and plot DE genes and exons for oligodendrocyte subtypes MOL2 and MOL5/6.
cds_olg_gene_exon.rds, which contains both gene and exon counts, is used in this notebook.

OL_DEE_Pfam_mapping.ipynb maps DEEs from MOL2 to their associated Pfam domains. This notebook utilizes the dataframe DE_exons_MOL2, which contains DEEs for MOL2 and is provided in Supplementary Table 3.

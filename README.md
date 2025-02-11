# maxquant_proteingroup_template
A pipeline for the analysis of MaxQuant Protein Group file

# Publication Reference
Dataset from below paper linked:

https://www.nature.com/articles/s41586-023-05927-7

https://proteomecentral.proteomexchange.org/cgi/GetDataset?ID=PXD029257

# Files

* `proteinGroups.txt` measurement file
* `sample_annotation.csv` file

# Preprocessing

* log2
* remove proteins with zero values

# Differential Analysis

* limma


# Biological Analysis

Reactome Pathways Download
https://reactome.org/download/current/UniProt2Reactome.txt

Once downloaded, the file has no column headers, make sure to name uniprot ID column `uniprotID`

* GSEA

# Export

* Limma Results
* Pathway NES Results
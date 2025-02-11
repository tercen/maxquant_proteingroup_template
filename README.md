# maxquant_proteingroup_template
A pipeline for the analysis of MaxQuant Protein Group file


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

make sure to name uniprot ID column `uniprotID`

* GSEA

# Export

* Limma Results
* Pathway NES Results
# Melanocytes_Tang2020
 R scripts and resources to accompany Tang et al 2020 manuscript
 
## Scripts:
File | Description
-----|------------
S01_tSNE.Rmd | Performs t-Distributed Stochastic Neighbor Embedding on clones to determine relatedness and confirm different cell tyoes
S02_RNA_DE_celltype.Rmd | Analyses RNA to identify genes significantly differentially expressed in different cell types, thereby confirming cell morphology
S03_MB_Signature_analysis.Rmd | Plots mutation burdens of clones and identifies the proportion of their mutations associated with previously defined mutation signatures
S04_RNA_MB_DE.Rmd | Identifies significantly differentially expressed genes associated with changes in mutation burden within one anatomic site
S05_RNA_sexchrom_dels.Rmd | Calculates coverage over sex chromosomes and creates t-SNE plot to identify clones with sex chromosome deletion

## Resource files:
File | Description | Used in script
-----|------------|---------
Ensembl_IDs.txt | List of Ensembl transcript IDs and associated gene names | S01, S02, S04, S05
ensemblIDS_chromosomes.txt | List of Ensembl transcript IDs, associated gene names, and the chromosome in which they reside | S05
exome_mutation_list_csq_UV_MAF_20200211.txt | Combined list of all validated or inferred mutations identified in exome data | S03
mutation_burdens_20200211.csv | Calculated mutation burdens for each clone | S03
mutation_burdens_plot_20200211.csv | Calculated mutation burdens for each clone reorganised in script S03 | S04
Signature7abc_PJ.csv | Mutation signatures as defined my Petljak et al 2019 | S03
ucsf_mutation_list_csq_UV_MAF_20200211.txt | Combined list of all validated or inferred mutations identified in UCSF500 data | S03

## Also included:

Direct output of RSEM gene quantification analysis.
An output for each clone is in the RNA/ directory

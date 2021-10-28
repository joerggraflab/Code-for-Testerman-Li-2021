# NAFLD-Shotgun-Metagenomes
This repository contains scripts and command logs used in Testerman et al., 2021. The primary documents are as follows.

1. https://github.com/todd-testerman/Code-for-Testerman-Li-2021/blob/main/R_phyloseq_microviz_ancom.md - This markdown document contains the majority of code used to generate figures and results in this paper. This includes the import of files produced by Metaphlan into phyloseq, alpha and beta diversity analyses using microViz, barplot generation using microViz, ANCOM analyses using ancom-bc, and figure creation and export with patchwork. 
2. https://github.com/todd-testerman/Code-for-Testerman-Li-2021/blob/main/script_human_removal.sh - This short shell script was used to run the 36 shotgun metagenomes through the kneaddata program to remove human-associated reads.
3. https://github.com/todd-testerman/Code-for-Testerman-Li-2021/blob/main/metaphlan_batch.sh - This short shell script performed the initial 
MetaPhlAn3 processing and taxonomic assignment for the metagenomes.
4. https://github.com/todd-testerman/Code-for-Testerman-Li-2021/blob/main/metaphlan_batch_w_bowtie2.sh - This short shell script added virus profiling of metagenomes using MetaPhlAn3 with bowtie2 files as input (to decreased analysis time).
5. https://github.com/todd-testerman/Code-for-Testerman-Li-2021/blob/main/concatenate_for_humann.sh - This short shell script was used to concatenate forward and reverse metagenome reads for each sample before input into humann3.
6. https://github.com/todd-testerman/Code-for-Testerman-Li-2021/blob/main/humann_batch.sh - This short shell script was used to run humann3 on the concatenated, cleaned metagenomes. 
7. https://github.com/todd-testerman/Code-for-Testerman-Li-2021/blob/main/humann_normalization_batch.sh - This short shell script performed normalization of the humann3 output files. 
8. https://github.com/todd-testerman/Code-for-Testerman-Li-2021/blob/main/Maaslin2_NAFLD_Metagenomes.md - This markdown document includes the commands used for Maaslin2 processing of humann3-processed pathway abundance files to identify differentially abundant pathways.

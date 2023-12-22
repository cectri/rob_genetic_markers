# Robustness quantification of a mutant library screen revealed key genetic markers in yeast 
##### This repository contains data as well as scripts used for the identification of genetic markers of microbial robustness in yeast.

**NOTE**: The main findings of the study are summarized below and in a study which is now submitted for peer-review.
We applied a previously published methodology [Quantification of microbial robustness in yeast](https://pubs.acs.org/doi/10.1021/acssynbio.1c00615) to more than 4000 yeast mutants from a genomic screen published by Michael Costanzo and colleagues in 2021 [Environmental robustness of the global yeast genetic interaction network](https://www.science.org/doi/10.1126/science.abf8424). The data analysis revealed potential genetic and metabolic targets of microbial robustness. To validate the analysis we replicated 14 non-essential gene deletions in **Saccharomyces cerevisiae** CEN.PK113-7D and cultivated the mutants in three distinct perturbation spaces resembling industrial bioprocesses. 

Main findings of the study: 
1.	Published datasets with phenotypic and genetic information can be explored with robustness analysis to investigate the connections between fitness, robustness, and metabolic processes.
2.	Despite the perturbation space, deleting MET28 notably enhances robustness in strain CEN.PK113-7D across three different spaces.
3.	The genetic background of the strain significantly impacts robustness outcomes.

&nbsp;  
&nbsp;  
This GitHub page includes:
 1. Scripts used to analyse the robusntess of mutants from Costanzo et.al /scripts/R_mutants
 2. Scripts to evaluate fitness and robusntess of the CEN.PK mutants in each perturbation space and a combination of all /scripts/FR_...Rmd
 3. Raw data from all the cultivations as well as plate layouts /datasets/
 4. Processed data from cultivation using scripts from number 2 /datasets/CPS(BPS-LHPS).rds

**NOTE** for each of the scripts mentioned above there is a corresponding .html page run on the available data. This is to facilitate the output and results visualization of the data of our study. 

&nbsp;  

Cecilia Trivellin, *cectri@chalmers.se*, Industrial Biotechnology Division, Chalmers University of Technology

Submission and final changes: 23-12-22

The scripts were tested with R Version: Version 2023.09.1+494 RStudio 
&nbsp;  
Mac OS Sonoma 14.1.2
&nbsp;  
The following R libraries were used in the scripts and referenced in the manuscript: 
&nbsp;  
tidyverse, deSolve, lattice, growthrates, Cairo, readxl, bbplot, ggplot2, ggvenn, VennDiagram, ggpubr, packcircles, RColorBrewer, patchwork, treemapify

&nbsp;  

--------

Acknowledgment of support: This material is based upon work supported by the Novo Nordisk Foundation grant DISTINGUISHED INVESTIGATOR 2019 - Research within biotechnology-based synthesis & production (#0055044).
Société Industrielle Lesaffre, Division Leaf, is kindly acknowledged for providing the Ethanol Red strain.
Credit is given to Michael Costanzo and his colleagues for their contributions, including publicly available datasets that served as the foundation for the analysis in this study.

&nbsp;  

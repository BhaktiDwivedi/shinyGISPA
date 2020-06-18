GISPA: A Method for Gene Integrated Set Profile Analysis 
========================================================

Authors
_______
Bhakti Dwivedi & Jeanne Kowalski


Maintainer
__________
Bhakti Dwivedi


Organization
____________
Biostatistics & Bioinformatics Shared Resource
Winship Cancer Institute
Emory University
Atlanta, GA 30322


Purpose
_______
Gene Integrated Set Profile Analysis (GISPA) is a method intended for the researchers who are interested in defining gene sets with similar, a priori specified molecular profile. GISPA method has been previosuly published in Nucleic Acids Research journal (Kowalski et al., 2016; PMID: 26826710).


Prerequisites
--------------
1) Download and install R or RStudio (version 3.1.2. or later) from https://cran.r-project.organd
2) Open R and install the required R packages:
install.packages( c("ggplot2", "genefilter", "changepoint", "HH", "lattice", "latticeExtra", "scatterplot3d", "data.table", "plyr", "knitr") )


Installation
------------
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")

BiocManager::install("GISPA")


Running GISPA from the GitHub
-----------------------------
Users can run GISPA locally by downloading the source code available from the GitHub: https://github.com/BhaktiDwivedi/GISPA


Vignette
------------
You can find the vignette for `GISPA` under [/vignettes/GISPA_manual.Rmd]


Bug Reports/Questions
_____________________
Please contact Bhakti Dwivedi, bhakti.dwivedi@emory.edu for questions, comments, or feature requests.


Funding
_______
This work is funded by the Leukemia and Lymphoma Society Translational Research Program Award (to Jeanne Kowalski); Georgia Research Alliance Scientist Award (Jeanne Kowalski); a Team Science Seed Funding from the Winship Cancer Institute of Emory University (Lawrence H. Boise, Sagar Lonial, Michael R. Rossi); Biostatistics and Bioinformatics Shared Resource of Winship Cancer Institute of Emory University and NIH/NCI [Award number P30CA138292, in part]. The content is solely the responsibility of the authors and does not necessarily represent the official views of the NIH.


Citation
________
Kowalski J, Dwivedi B, Newman S, Switchenko JM, Pauly R, Gutman DA, Arora J, Gandhi K, Ainslie K, Doho G, Qin Z, Moreno CS, Rossi MR, Vertino PM, Lonial S, Bernal-Mizrachi L, Boise LH. Gene integrated set profile analysis: a context-based approach for inferring biological endpoints. Nucleic Acids Res. 2016 Apr 20;44(7):e69. doi: 10.1093/nar/gkv1503. Epub 2016 Jan 29. PubMed PMID: 26826710; PubMed Central PMCID: PMC4838358.

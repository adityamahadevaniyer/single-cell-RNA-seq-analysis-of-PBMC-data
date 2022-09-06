# single-cell-RNA-seq-analysis-of-PBMC-data

I have used the PBMC single cell data from the 10X and analyzed using the latest tools.

Once I got the processed files from the website, I performed-
QC- scater package
Cell cycle scoring - scater
Normalization, Dimensionality Reduction, Clustering, plots - Seurat
Data Integration- Harmony, Seurat (merge)
Differential expression - scran, scater
Trajector inference- Monocle


Currently I am analyzing single-cell RNA-seq obtained in DO EBs (Embryonic bodies) in the Baker lab. For this, I will be using the demultiplexing pipeline by Chris Mcginnis (https://github.com/chris-mcginnis-ucsf/MULTI-seq) and then perform Cell ranger and Kallisto-bustools for alignment and getting the matrices. I can then use the Seurat pipeline given here for further analysis. 

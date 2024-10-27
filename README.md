This Github repository contains script and preliminary html reports from analysis of bulk RNA-seq samples obtained from mouse heart and liver across two sampling points. The sequence of scripts needed to be executed are in numerical order (01,02 and so on). 

I couldn't execute the processing of FASTQs using the nf-core pipeline due to memory issues on my personal laptop. Therefore, to mimic the similar design of the study, I processed the count matrix from Mansingh et al, 2024 to perform DEG (differential gene expression) and pathway-analysis along with other exploratory analysis using the count matrix. The count matrix is available for download here https://github.com/adityamiyer-personal/Bulk-RNA-seq-analysis/blob/main/scripts/Mansingh2024_expression_matrix.txt.  

Script for Mansingh et al data processing of the count matrix - https://github.com/adityamiyer-personal/Bulk-RNA-seq-analysis/blob/main/scripts/DGE_pathwayanalysis_Mansingh2024countmatrix.qmd

HTML report rendered from the above quarto document - https://github.com/adityamiyer-personal/Bulk-RNA-seq-analysis/blob/main/scripts/DGE_pathwayanalysis_Mansingh2024countmatrix.html (Please download the report to the PC and the code has been embedded along with the results).


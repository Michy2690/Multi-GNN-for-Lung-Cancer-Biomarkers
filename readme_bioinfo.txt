README

DATASET -> directory "lung"

CODICE -> directory "BioInfo"
Preprocessing gene expression, methylation, PPI links, illumina 27 annotations -> Dataframe.ipynb

Patient classification tumor/normal (with only gene expression or with combined data) -> Patient Classification.ipynb
Patient classification tumor/normal (with only methylation data) -> Methylation Classification.ipynb (until section "Tumor/Normal classification")

Combination with Learnable Layer and Combination Network training -> Expression_Meth_Combination.ipynb

Application of Louvain to Gene Expression -> Louvain_Gene.ipynb (until section "Louvain with edges that consider correlation")
Application of Louvain to Gene and Methylation Data (combination of gene and methylation with a-priori integration or with learnable layer) -> Louvain_Meth.ipynb (until section "Louvain with edges that consider correlation, application of WGCNA")

Biomarker identification and comparison between Louvain, Lasso, SVM RFE, PCA and Select KBest -> Methods.ipynb (The first part works with gene expression, the second with combined data using a-priori integration and the third with combined data using the learnable layer)
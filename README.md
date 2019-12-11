# ADNI
 predict ADAS and MMSE score based on genotype

## Dependencies 
### python packages
python3  
numpy  
tensorflow2  
sklearn  
pandas  
matplotlib  
rpy2  
### R package
glmnet  

## Data 
Here is only the description, not public download. Because the access permission should apply from The Alzheimer's Disease Neuroimaging Initiative (ADNI, http://adni.loni.usc.edu).   
The genetic data include:  
(1) ADNI_JansenNG_33gene_unimputed.bed  
(2) ADNI_JansenNG_33gene_unimputed.fam  
(3) ADNI_JansenNG_33gene_unimputed.bim  
The selected ADAS subjects and scores file which appear both in genetic and image data is:
(1) ADAS_selected.csv  
The selected MMSE subjects and scores file is:  
(2) MMSE_selected.csv  
For more information about the scores, please check https://adni.loni.usc.edu/wp-content/uploads/2012/08/instruction-about-data.pdf

## Methods
Lasso  
CNN  
CNN with pretrained representaiton by autoencoder  


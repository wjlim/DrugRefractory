# DrugRefractory
### Author: Won-Jun Lim
### Contact: cerutx@gmail.com

This workflow performs matrix factorization using MOFA on multi-omics data to find biomarkers that best explain the phenotype. The phenotype used here is the drug response of olaparib. The identified biomarker candidates propose predictive models for classifying the phenotype using Support Vector Machine, Random Forest, and Siamese Neural Network.

## MOFA.activites.olaparib.ipynb
* This is a MOFA workflow that finds important biomarker candidates from multi-omics data. The identified biomarkers are used to predict drug response in ovarian cancer patients and breast cancer patients in TCGA. The first part of the code consists of MOFA analysis, and the second part applies the Siamese network classifier for model prediction.
## MOFA.siamese.ipynb
* This notebook uses the biomarker candidates identified from MOFA to create a Siamese neural network and predict drug response.
## Evaluate_SNN.GDSC.ipynb
* This notebook uses external datasets from the Genomics of Drug Sensitivity in Cancer (GDSC) to test the performance of the model.
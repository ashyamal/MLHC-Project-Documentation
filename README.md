## About
"Imaging-based prediction of transcriptional subtypes in Alzheimer’s disease"

This project was a team-based class project for Machine Learning for Healthcare, Spring 2023. My specific role was performing gene-set analysis on brain imaging GWAS datasets to understand Alzheimer’s subtype genetics.

## Abstract

This study explores the application of genetic information, and deep learning techniques to predict Alzheimer’s Disease (AD). For brain MRI image analysis, we compared the results using Convolution Neural Networks (CNN) built from scratch, CNN transfer learning, and Vision Transformers (ViT). Our vision transformer model achieved the best performance on the test set with 98.57% accuracy. We explored the method using ViT in 3D brain MRI image analysis by treating each 3D patch as a vector to feed into the transformer. Using CNN/ViT model, we also extracted feature representations of brain MRI images for multimodal usage. By combining feature encoders from image and genetic deep learning models, we are able to further improve performance using a self-supervised contrastive learning pipeline. We show that feature explanation techniques can attribute genetic contributions to image embeddings, even after fine-tuning, which can be effective in understanding the genetic impact of neuro-imaging in Alzheimer’s Disease. For the first time to our knowledge, we demonstrated the feasibility of cell type-specific PGS and their improved performance in predicting white blood cell count in PBMCs, as well as a more complex phenotype, gray matter volume in the frontal cortex.

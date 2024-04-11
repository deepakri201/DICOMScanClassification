# DICOMScanClassification

This repository holds the code for the MIDL 2024 short paper submission "Automatic classification of prostate MR series type using image content and metadata". 

## Abstract

With the wealth of medical image data, efficient curation is essential. Assigning the sequence type to magnetic resonance images is necessary for scientific studies and artificial intelligence-based tasks. Incomplete or missing metadata prevents effective automation, leading to time-consuming and error-prone processes by clinicians. We propose a deep-learning method for classification of prostate cancer scanning sequences based on a combination of image data and DICOM metadata. We demonstrate superior results compared to metadata or image data alone, and make our code publicly available at https://github.com/deepakri201/DICOMScanClassification.

## Code

[DICOMTagClassification_ImageAndMetadata_setup_exp3.ipynb](DICOMTagClassification_ImageAndMetadata_setup_exp3.ipynb)
This notebook is for querying Imaging Data Commons data, and obtaining the appropriate metadata from the DICOM files. 

[DICOMTagClassification_ImageAndMetadata_train_and_test_exp3.ipynb](DICOMTagClassification_ImageAndMetadata_train_and_test_exp3.ipynb) This notebook is for the training and test data setup, running training/validation for the three models, and for running inference. Figures and tables are also produced in this notebook. 

## Notes

Further details will be added to this page about how to use the code.



Deepa Krishnaswamy (dkrishnaswamy@bwh.harvard.edu), April 2024, Brigham and Women's Hospital

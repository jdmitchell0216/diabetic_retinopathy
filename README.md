# Diabetic Retinopathy
Diagnosis of diabetic retinopathy can be done through the analysis of patient retinal scans. This repository is an attempt to produce an accurate diagnosis of diabetic retinopathy using CNNs. The dataset and project outlines can be found in the [APTOS 2019 Blindness Detection](https://www.kaggle.com/c/aptos2019-blindness-detection) competition on kaggle.

The project has been set up on Google Cloud Platform (GCP) so some of the work in the setup notebook will not be applicable if one is attempting to run these notebooks locally.

A series of blog posts are being written on this project on [Medium](https://medium.com/@jdmitchell0216/diabetic-retinopathy-ml-diagnosis-introduction-eda-and-baseline-model-9b2381bbac28)

Currently, the model makes classifications in two stages. The first stage distinguishes between images with no signs of diabetic retinopathy (label 0) and those that do (labels 1-4). Images that are not classified as 0 continue into the second stage, where they are classified as one of the non-zero labels.

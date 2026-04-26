# Practical Homework 2 — SVM 

DATA 5322- Statistical Machine Learning 2
Author: Sravya Murala

## Overview
This project predicts cancer history (CANCEREV) from 8 lifestyle and 
demographic variables in NHIS 2022 data, comparing Linear, Radial (RBF), 
and Polynomial SVM kernels.

## Files
- `Practical-Homework-2.Rmd` — full R Markdown source code
- `Practical-Homework-2.html` — knitted HTML output
- `Practical Homework 2 SVM_Poster.pdf` — poster 
- `nhis_2022.csv` — NHIS 2022 dataset (from IPUMS Health Surveys)
- `svm_decision_boundary_image.py` — Python script for SVM decision boundary diagram (R plotting was insufficient for this visualization)

## How to reproduce
1. Open `Practical-Homework-2.Rmd` in RStudio
2. Run all chunks or click Knit.

## Results summary
All three SVM kernels achieve ~0.78 test AUC. Permutation importance 
shows AGE accounts for almost all predictive signal. Linear kernel is 
recommended as the most practical choice given equivalent performance.

## Data citation
Blewett, L.A., et al. IPUMS Health Surveys: NHIS Version 7.4. IPUMS, 2024.
https://doi.org/10.18128/D070.V7.4

# Hyperspectral Data Synthesis for Wastewater Analysis

This repository contains a data synthesis project using CTGAN and TVAE to generate hyperspectral data related to wastewater turbidity. The goal is to support environmental monitoring and data analysis efforts by providing enhanced datasets for model training and research.

## Results Overview

The synthetic data generated achieved an Overall Quality Score of 88.46%.

Properties:
- Column Shapes: 94.13%
- Column Pair Trends: 82.79%

## Visual Results

Comparison of Continuous Spectra
![download](https://github.com/AbhinitMahajan/Generating-Spectral-Data-/assets/82913786/6e637f35-3cff-4b05-b99b-fef30b3faa4e)
*Figure 1: Comparison of continuous spectra between real and synthetic data, illustrating the model's ability to capture the overall trend across different wavelengths.*

![Distribution of Tur Values](image2.png)
*Figure 2: Histogram of turbidity values comparing the distribution between real and synthetic datasets, showing how closely the synthetic data matches the real data distribution.*

![Real vs. Synthetic Data for column '490'](image3.png)
*Figure 3: Density plot for the spectral feature at 490 nm, contrasting the real and synthetic data to highlight the synthesis quality at a specific wavelength.*

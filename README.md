# Hyperspectral Data Synthesis for Wastewater Analysis

This repository contains a data synthesis project using CTGAN and TVAE to generate hyperspectral data related to wastewater turbidity. The goal is to support environmental monitoring and data analysis efforts by providing enhanced datasets for model training and research.

## Results Overview

The synthetic data generated achieved an Overall Quality Score of 88.46%.

Properties:
- Column Shapes: 94.13%
- Column Pair Trends: 82.79%

## Visual Results

### Comparison of Continuous Spectra
![download (1)](https://github.com/AbhinitMahajan/Generating-Spectral-Data-/assets/82913786/301f577b-4df9-424a-8854-f06ea789fcbc)
*Figure 1: Comparison of continuous spectra between real and synthetic data, illustrating the model's ability to capture the overall trend across different wavelengths.*

### Distribution of Tur Values
![download](https://github.com/AbhinitMahajan/Generating-Spectral-Data-/assets/82913786/4ca5294a-a98d-4563-90c9-9f768cb4b724)
*Figure 2: Histogram of turbidity values comparing the distribution between real and synthetic datasets, showing how closely the synthetic data matches the real data distribution.*

### Real vs. Synthetic Data for column '490'
![newplot](https://github.com/AbhinitMahajan/Generating-Spectral-Data-/assets/82913786/af274968-330f-4330-a3eb-61f386eb07ac)
*Figure 3: Density plot for the spectral feature at 490 nm, contrasting the real and synthetic data to highlight the synthesis quality at a specific wavelength.*

### References 
- https://docs.sdv.dev/sdv/ : A library that contains information regarding the code present. Helps you produce synthetic tabular data 
- GenModels_Parameters.pdf: Gives you an insight into the model parameters for effective training 
- https://docs.sdv.dev/sdv/single-table-data/sampling/sample-realistic-data: After training model. While generating synthetic data out from trained model; parameters that are used in the generation
- https://www.analyticsvidhya.com/blog/2021/05/tuning-the-hyperparameters-and-layers-of-neural-network-deep-learning/ : neural networks hyperparameter understandig 
- https://www.youtube.com/watch?v=3G5hWM6jqPk : Complete understanding for generative modelling 
- https://docs.google.com/document/d/1JfBW7PVWk_BI9ElmlvWNu-VhNdkZudartsZfPkbbmsY/edit: Generative modelling notes 

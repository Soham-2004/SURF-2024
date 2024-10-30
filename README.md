# Helium-3 Rich Period Detection in SEP Events

This repository contains jupyter notebooks for studying Solar Energetic Particle (SEP) events to detect Helium-3 (He-3) rich periods using advanced machine learning techniques. The analysis is based on data from the Advanced Composition Explorer's Solar Isotope Spectrometer (ACE/SIS), spanning the years 2017 to 2024.

## Project Description

This project aims to advance our understanding of SEP events by using both supervised and unsupervised machine learning models to enhance the detection of He-3 rich periods. These periods are important for studying solar phenomena and assessing their impact on space weather.

### Models Employed
- **Supervised Learning Model**: Uses a recurrent neural network to classify periods as He-3 rich based on training with labeled mass histogram data. This model helps to quantify and predict He-3 enrichments more accurately than traditional methods. We treat the task as a binary classification task.
- **Unsupervised Learning Models**:
  - **K-means Clustering**: Applied to identify latent patterns in the data, giving us new ways to categorize SEP events without predefined labels.
  - **HDBSCAN Clustering**: Uses a density-based approach to detect clusters within the data, allowing us to identify dense groups in the sparse dataset.
  - **Random Forest Classifier**: Gives us a robust classification method that considers non-linear interactions between features, enhancing model interpretability and accuracy.

## Data
The data comprises hourly mass histograms captured by the ACE/SIS instrument. Each histogram represents solar energetic particle counts across 60 mass bins, focusing on particles within the mass range of 2 to 5 atomic mass units (amu), which is crucial for detecting He-3 and He-4 isotopes.

## Installation and Usage
All modes were run on a Google Colab T400 GPU. All required libraries have been added to the code using the pip install command

## Results
The implemented models demonstrated significant improvements in identifying He-3 rich events, with machine learning approaches providing new insights about the nature of HE-3 rich solar events. Detailed results and discussions on model performance and implications for solar physics are shown within each notebook.

## Authors
- **Soham Dasgupta**

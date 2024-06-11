# Identifying Features for Keloid Scars Subtyping using K-modes clustering

## Project Overview

This project applies the K-Modes clustering algorithm to identify predictive features of keloid scar development by analyzing patterns in ICD-10 medical codes from patient histories. The aim is to uncover risk factors that contribute to the development of keloid scars to enhance prevention and management strategies.

## Methods

### Dataset
The dataset comprises ICD-10 medical codes extracted from the UK Biobank, focusing on individuals diagnosed with hypertrophic disorders of the skin, which includes codes relevant to keloid scarring such as L90.5 (Scar conditions and fibrosis of the skin), L91.0 (Keloid Scar), and various codes pertaining to burns and injuries.

### Data Preprocessing
Data was preprocessed to select individuals with hypertrophic skin disorders, followed by encoding ICD-10 codes relevant to our study. The resulting dataset was used to apply K-Modes clustering.

### Clustering Analysis
K-Modes clustering was utilized due to its suitability for categorical data. The number of clusters was determined based on consistency of results across multiple trials, with the best outcomes observed between 2 and 10 clusters. Features showing the most predictive power for keloid scar formation were identified through chi-square tests.

## Results

The clustering analysis identified specific ICD-10 codes as significant predictors of keloid scar formation. Notably, codes related to burns and severe skin injuries were frequently found in clusters with a high prevalence of keloid scars, underscoring their significant role as risk factors. The features with the highest chi-square values were:
- L90.5 (Scar conditions and fibrosis of the skin)
- T22 (Burns and corrosion of shoulder and upper limb)
- T21 (Burns and corrosion of trunk)
- T25 (Burns and corrosion of ankle and foot)

The chi-square test results indicated strong associations between these conditions and the likelihood of developing keloid scars, with the presence of scar conditions and fibrosis (L90.5) showing a particularly strong predictive relationship.

The results from this study provide valuable insights into the risk factors associated with keloid scars, highlighting the potential for targeted medical interventions based on patient-specific ICD-10 profiles.

# T1w Fractal Dimension Repository

This repository contains de-identified example data and resources for computing fractal dimensions from T1-weighted MRI scans. It includes code and patient-derived, de-identified data for analysis and processing. The repository is part of ongoing research in the Radiology-Morrison-lab-UCSF. We kindly ask that you cite our article when using materials from this repository: `Schoen, D., Deutsch, S., Mehta, J. et al. Boundary complexity of cortical and subcortical areas predicts deep brain stimulation outcomes in Parkinson’s disease. Nat Commun 16, 5590 (2025). https://doi.org/10.1038/s41467-025-60695-4`:

## Contents

- **`ExamplePatient_FractalDimension_ROIS.csv`**: 
  - A CSV file containing fractal dimension values for 90 regions of interest (ROIs) based on the AAL atlas.
- **`ExamplePatient_T1w_brain.nii.gz`**: 
  - A de-identified, skull-stripped T1-weighted MRI scan in NIfTI format with identifying features (ears, nose, mouth) removed.
- **`LEDD_Score_ExamplePatient.xlsx`**: 
  - An Excel file with LEDD scores for the example patient.
- **`MDSUPDRS_Scores_ExamplePatient.xlsx`**: 
  - An Excel file with MDS-UPDRS scores for the example patient.
- **`FeatureSelection_and_ClassificatioinLearning.ipynb`**: 
  - A jupyter notebook (python 3.7) that performs feature selection and also performs a classification learning task using HGNNs from the DHG package in PyTorch
- **`T1_metrics_FD_MDSUPDRS.xlsx`**: 
  - An Excel file with all features and charecteristics used in the predictive modeling for our cohort.

## Data De-Identification

The included example patient data is derived from a real patient but has been de-identified to comply with ethical guidelines:
- All dates (e.g., surgeries and follow-up visits) have been altered, but the time intervals between events remain consistent to ensure accurate calculations.
- The T1-weighted MRI scan has been skull-stripped to remove identifiable features, such as ears, nose, and mouth.
- Metadata an


## Future Additions

This repository will soon include:
- **Code**:
  - Scripts for processing weighted MRI images and calculating fractal dimensions.
  - Statistical analysis scripts for downstream interpretation and visualization.
- **Data**:
  - De-identified MRI scans and associated metadata.
  - All data will be made publicly available through [OpenNeuro](https://openneuro.org/) upon completion of ongoing analyses.

## Licenses

**Copyright 2025 UCSF**

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at:  
[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

- All code files in this repository are licensed under the Apache License 2.0.
- `LEDD_Score_ExamplePatient.xlsx`, `MDSUPDRS_Scores_ExamplePatient.xlsx`, `T1_metrics_FD_MDSUPDRS.xlsx`, and `ExamplePatient_T1w_brain.nii.gz` were acquired at the University of California San Francisco and are licensed under the [Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/).

## Acknowledgments

This project is part of ongoing research in the Radiology-Morrison-lab-UCSF. Special thanks to all contributors and collaborators involved in this work.

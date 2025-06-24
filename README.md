# Lagged predictors of Psychological Capital in junior high school students: A supervised Machine Learning approach

Author: **Enrico Perinelli**  
Affiliation: Department of Psychology and Cognitive Science, University of Trento, Italy  
Email: enrico.perinelli@unitn.it  
License: [![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![Creative Commons License](https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)  

---

## Overview

This repository contains the Jupyter notebooks and Python code used in the data analyses presented in the article below, which investigates longitudinal predictors of Psychological Capital (PsyCap) in junior high school students through supervised machine learning and XAI techniques.  

> Perinelli, E., Stella, M., Bizzego, A., Pisanu, F., & Fraccaroli, F. (accepted). Lagged predictors of Psychological Capital in junior high school students: A supervised Machine Learning approach.  

---

## Repository Structure

- `1_PsyCapML_seeded.ipynb`: Full modeling pipeline (data preparation, training, evaluation, feature importance, and SHAP analysis) using a fixed random seed to ensure full reproducibility.
- `2_PsyCapML_unseeded1.ipynb`, `3_PsyCapML_unseeded2.ipynb`, `4_PsyCapML_unseeded3.ipynb`: First, second, and third run of the pipeline without a fixed seed, to assess the generalizability of performance metrics and feature importance under random data splits.
- `5_PsyCapML_seeded_RemovePsyCapT1.ipynb`: Replication of the seeded pipeline excluding PsyCap at T1 from the features, to assess the predictive power of other variables beyond the autoregressive effect. This notebook corresponds to the *Complementary Analyses* section of the paper.

---

## Data Availability

The data used in this study were collected as part of a school-based educational project. Due to ethical and legal restrictions, the datasets cannot be publicly shared.

---

## License

This work is licensed under the  
**Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)**.  
Read more: [https://creativecommons.org/licenses/by-nc-sa/4.0/](https://creativecommons.org/licenses/by-nc-sa/4.0/)
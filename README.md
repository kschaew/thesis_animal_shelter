
```markdown
# Classifying Long-Stay Animals in Shelters

**Author:** Chaewon Kim  
**MSc Thesis Project**  
**Tilburg University — Data Science and Society**

## Overview

This repository contains the code used for my MSc thesis on predicting long-stay risk among animals in shelters. The project uses Dallas Animal Shelter intake and outcome records, combined with census tract-level socioeconomic variables, to classify animals that are at risk of becoming long-stay cases.

The analysis compares machine learning models using shelter-record variables and socioeconomic features to evaluate whether socioeconomic context adds predictive value beyond intake-level shelter information.

## Repository Contents

- `notebooks/`: Jupyter notebooks for data cleaning, preprocessing, modeling, and evaluation
- `outputs/`: Selected result tables and figures
- `requirements.txt`: Python package requirements
- `README.md`: Repository description

## Data Access

The dataset used in this thesis is stored separately and is not included directly in this repository.

Data access is restricted to Tilburg University accounts and can be accessed through the link below:

[Access the thesis dataset via Google Drive](https://drive.google.com/drive/folders/1GgUTDuZO9hRly3Ek43_TMiqt36KDxUQD?usp=drive_link)

## Data Sources

The main shelter dataset is based on Dallas Animal Shelter Intake and Outcome Records. Socioeconomic variables were obtained from the 2019 American Community Survey 5-year estimates and linked at the census tract level.

## Project Workflow

The analysis follows the main stages of the thesis workflow:

1. Data cleaning and exploratory data analysis
2. Feature engineering and socioeconomic data linkage
3. Preprocessing and train-test splitting
4. Model training and hyperparameter tuning
5. Model evaluation, error analysis, and feature interpretation

## Notes

Large data files, intermediate processed datasets, trained model objects, and local output files are not included in this repository due to file size and access restrictions.

## Citation

If using or referring to this repository, please cite the thesis:

Kim, C. (2026). *Classifying Long-Stay Animals in Shelters*. MSc Thesis, Tilburg University.

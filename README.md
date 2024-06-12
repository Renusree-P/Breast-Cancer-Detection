# Breast-Cancer-Detection
## Overview
Breast cancer is a serious problem increasing at a rapid rate among women all over the world.
## Table of Contents

## Objectives
1) To identify if a person has cancer or not
2) To make a model to predict if the patient is cancer prone or not
3) Classifying the cancer based on Image Classification

## Dataset
This Breast Cancer dataset is taken from Kaggle
 - [Download here](https://www.kaggle.com/datasets/raghadalharbi/breast-cancer-gene-expression-profiles-metabric)

## Methodology
The model was developed using the following steps:
#### Data Collection:
- For getting the required data, searched through many sources
- ultimately settled with Kaggle dataset

#### Data Preprocessing:
- This dataset has 693 columns
- Since developing a model with this many columns as an academic project is out of scope, we deleted some columns
- The deleted columns were mainly related to medical terms, which require vast knowledge in that area and are understood only by medical practitioners and scientists.
- Considered 17 columns that were identified as important in our research

#### Data Inspection:
- The dataset after initial cleaning contains a lot of missing values
- For numerical variables, the missing values are replaced with the median
- For categorical variables, the missing values are replaced with 'NA'

#### Exploratory Data Analysis:
-  Statistical summeries and viualizations of variables are generated to understand the data
-  Heat map, correlations are done to find out the outliers in the data
  
#### Data Transformation:
- The data is normalised
- Feature engineering is done

####  Model training:

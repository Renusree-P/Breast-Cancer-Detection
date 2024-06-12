# Breast-Cancer-Detection
## Overview
Breast cancer is a serious problem increasing at a rapid rate among women all over the world. Early detection of breast cancer will save lot of lives. So, let's create a model using machine learning algorithms to detect breast cancer at early stages.

## Table of Contents
 - [Objectives](#objectives)
 - [Dataset](#dataset)
 - [Methodology](#methodology)
    - [1.Data Collection](#1-data-collection)
    - [2.Data Preprocessing:]
    - [3.Data Inspection:]
    - [4.Exploratory Data Analysis:]
    - [5.Data Transformation:]
    - [6.Model training:]
    - [7.Model Evaluation]
## Objectives
1) To identify if a person has cancer or not
2) To make a model to predict if the patient is cancer prone or not
3) Classifying the cancer based on Image Classification

## Dataset
This Breast Cancer dataset is taken from Kaggle
 - [Download here](https://www.kaggle.com/datasets/raghadalharbi/breast-cancer-gene-expression-profiles-metabric)

## Methodology
The model was developed using the following steps:
#### 1.Data Collection:
- For getting the required data, searched through many sources
- ultimately settled with Kaggle dataset

#### 2.Data Preprocessing:
- This dataset has 693 columns
- Since developing a model with this many columns as an academic project is out of scope, we deleted some columns
- The deleted columns were mainly related to medical terms, which require vast knowledge in that area and are understood only by medical practitioners and scientists.
- Considered 17 columns that were identified as important in our research

#### 3.Data Inspection:
- The dataset after initial cleaning contains a lot of missing values
- For numerical variables, the missing values are replaced with the median
- For categorical variables, the missing values are replaced with 'NA'

#### 4.Exploratory Data Analysis:
-  Statistical summeries and viualizations of variables are generated to understand the data
-  Heat map, correlations are done to find out the outliers in the data
  
#### 5.Data Transformation:
- The data is normalised
- Feature engineering is done

####  6.Model training:
- The dataset is divided into training and testing sets
- The model is trained on Decision Tree and Random Forest models

#### 7.Model Evaluation
- Each model is evaluated on metrics like precision, recall, accuracy, f-1 score
- The performance of the two models is compared using these metrics

## Conclusion
This model can be used for earlier detection of the breast cancer. Between the two models, the Random Forest model was better than Decision tree model.

## Challenges
- The number of variables used to develop this model were limited. For this model to work accurately in real world scenario, a number of other variables must also be considered.
- Further tuning of this model can be done while making sure that precision and accuracy are improved.

## Future work
- Improving the accuracy
- Other imporatnt variables can be considered
- The model can be trained on many more machine learning algorithms
- Integrate the model with the Electronic Health Records (ERH) to implement in the real-world

## Image Classification
#### Objective
To classify the cells as cancerous or not by using Image classification 

#### Dataset
- The dataset was obtained from Kaggle
  - [Download here](https://www.kaggle.com/code/damodharrao/starter-breast-histopathology-images-41da081a-1/input)

#### Implementation
- Create a model
- Train the model so that it can distingush the images as positive or negative to cancer
- Test the model for accuracy

#### Future work
This model is not accurately reading the images. We are working on this model.
     

# Diabetes Prediction Project

This project involves predicting whether a person has diabetes based on health indicators and lifestyle factors. The model is trained using a Random Forest classifier and incorporates techniques for handling class imbalance.

## Table of Contents

- [Overview](#overview)
- [Data](#data)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Model Evaluation](#model-evaluation)
- [Results](#results)
- [License](#license)

## Overview

This project uses a dataset containing health metrics such as blood glucose levels, BMI, and age, to predict the likelihood of a person having diabetes. The model leverages a Random Forest classifier with hyperparameter tuning and resampling techniques (SMOTE and RandomUnderSampler) to address class imbalance.

## Data

The dataset includes the following features:
- `age`: Age of the individual.
- `BMI`: Body Mass Index.
- `HbA1c_level`: Average blood glucose level over the past 2-3 months.
- `blood_glucose_level`: Current blood glucose level.
- `hypertension`: Whether the person has hypertension (1) or not (0).
- `heart_disease`: Whether the person has heart disease (1) or not (0).
- `gender`: Gender of the individual (Male/Female).
- `smoking_history`: Smoking history (e.g., current, past, none).
- `diabetes`: Target variable (1 for diabetic, 0 for non-diabetic).

## Requirements

To run this project, you'll need to install the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn

You can install these dependencies using:


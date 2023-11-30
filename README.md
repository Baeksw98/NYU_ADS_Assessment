# Analysis of a Home Credit Default Risk ADS

Authors: Sangwon Baek and Simone Rittenhouse  
Institution: Center for Data Science, New York University  
Course: DS-UA 202: Responsible Data Science  
Professor: George Wood  

## Overview

This repository contains the analysis of an Automated Decision System (ADS) developed by Will Koehrsen for the Home Credit loan default risk Kaggle competition. The ADS aims to predict loan repayment likelihood using historical data, assisting individuals with limited credit history in obtaining loans.

## Table of Contents

- [Background](#Background)
- [Input Data](#Input-Data)
- [Implementation and Validation](#Implementation-and-Validation)
- [Outcomes and Performance Analysis](#Outcomes-and-Performance-Analysis)
- [Fairness and Diversity Measures](#Fairness-and-Diversity-Measures)
- [Classification Explanations](#Classification-Explanations)
- [Summary and Conclusions](#Summary-and-Conclusions)
- [References](#References)

## Background

The ADS was designed to predict the likelihood of loan repayment, using various features like income, age, and gender. It serves as a training tool for data science projects, balancing simplicity and prediction accuracy.

## Input Data

The ADS utilized primary training/test loan application data, comprising demographics, credit history, and other features. The training set included 122 features, of which 106 were numeric and 16 categorical.

## Implementation and Validation

The model involved preprocessing steps like encoding categorical variables and data cleaning. It employed logistic regression and a random forest model, the latter using the RandomForestClassifier class from sklearn.ensemble.

## Outcomes and Performance Analysis

Performance across subpopulations was assessed, revealing class imbalances and the impact of demographic factors on loan repayment predictions.

## Fairness and Diversity Measures

Fairness was evaluated using error rates and prediction probabilities across different groups, focusing on gender and age as sensitive attributes.

## Classification Explanations

SP-LIME was utilized to generate explanations for the model's predictions, highlighting the importance of certain features in the classification process.

## Summary and Conclusions

The analysis identified several shortcomings in the ADS, including issues with data fairness, transparency, and model performance. The model showed bias against certain groups and failed to achieve a high AUC score. Improvements are suggested to enhance model fairness and accuracy.

## References

- Baek, S., & Rittenhouse, S. (2022). Analysis of a Home Credit Default Risk Automated Decision System. 

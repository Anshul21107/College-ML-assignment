# Heart Disease Prediction using Bayesian Models

This repository encapsulates the culmination of the CSSE11 assignment, presenting a comprehensive exploration of advanced predictive modeling techniques on a real-world dataset. The modeling techniques applied to predict heart disease based on a real-world dataset. The primary focus revolves around leveraging Bayesian modeling techniques to predict the likelihood of heart disease occurrence using various patient health metrics and indicators.

## Table of Contents

1. [Introduction](#introduction)
   - [Problem Statement](#problem-statement)
2. [Methodology](#methodology)
   - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
   - [Data Preprocessing](#data-preprocessing)
   - [Model Implementation](#model-implementation)
3. [Results](#results)
4. [Conclusion](#conclusion)

## Introduction

### Problem Statement

The project aims to predict the likelihood of heart disease occurrence by employing Bayesian modeling techniques. It seeks to establish a robust predictive model using patient health metrics and other relevant features available in the dataset. This predictive model intends to assist in early detection and proactive measures for potential heart disease cases.

## Methodology

### Exploratory Data Analysis (EDA)

A meticulous Exploratory Data Analysis (EDA) lays the groundwork for understanding the dataset. Utilizing visualization techniques, such as seaborn's visualizations, the project delves into understanding the relationships between various health metrics and the presence or absence of heart disease.

### Data Preprocessing

The dataset undergoes meticulous preprocessing, including handling categorical variables, ensuring data consistency, and encoding categorical variables for compatibility with Bayesian Network modeling. This preprocessing phase aims to refine and prepare the dataset for model implementation.

### Model Implementation

#### Bayesian Network

A Bayesian Network, crafted using libraries like `pgmpy`, forms the core of the predictive model. This model is designed to capture complex relationships between patient health metrics and the likelihood of heart disease occurrence. The Bayesian Network aligns with the theoretical foundations of probabilistic graphical models.

## Results

The Bayesian Network model showcases its efficacy with notable accuracy and interpretability metrics on the test dataset. Results from other models or ensemble techniques, if employed, are also presented here.

## Conclusion

In conclusion, this project seamlessly integrates theoretical foundations with practical implementation in predicting heart disease using Bayesian modeling. The Bayesian Network model provides interpretability and insight into variable dependencies, showcasing its potential impact in early detection. This holistic approach unlocks valuable insights for potential applications in proactive healthcare and disease prediction.

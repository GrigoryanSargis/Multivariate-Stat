# Multivariate-Stat
## Overview

This repository contains the analysis and results of a multivariate statistical project using the "Math Students" dataset. The goal of the project is to understand the factors influencing students' academic performance through various statistical techniques including linear regression and Principal Component Analysis (PCA).


## Dataset
The dataset used in this project is the "Math Students" dataset, which includes information on students' demographics, academic performance, and other related factors.

## Analysis
### Linear Regression
The linear regression analysis aims to predict students' final grades based on various independent variables. The significant predictors identified include:

* Failures: Number of past class failures.
* Absences: Number of school absences.
- Weekend Alcohol Consumption (Walc): Level of alcohol consumption on weekends.
- School Support (schoolsup_yes): Whether the student receives additional educational support.

## Principal Component Analysis (PCA)
PCA is used to reduce the dimensionality of the dataset while retaining most of the variability. The first two principal components explain a significant portion of the variance in the data:

- PC1: 23.9% of the variance.
- PC2: 13.1% of the variance.

## Correlation Circle
The correlation circle plot visualizes the relationships between the original variables and the principal components. Key insights include:

- Failures and Absences are positively correlated with the first principal component (PC1).
- Weekend Alcohol Consumption (Walc) and Going Out with Friends (goout) are positively correlated with the second principal component (PC2).
- School Support (schoolsup_yes) is negatively correlated with both principal components.

# How to Run
1. Clone the repository:
  git clone https://github.com/GrigoryanSargis/Multivariate-Stat.git
2. Navigate to the project directory:
   cd Multivariate-Stat
3. Open the Jupyter Notebook Multivariate_Stat.ipynb to explore the analysis:
   jupyter notebook Multivariate_Stat.ipynb




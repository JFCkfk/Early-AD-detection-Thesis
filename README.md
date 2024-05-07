# Early-AD-detection-Thesis
Author: Junfan Chen jc11573@nyu.edu

This Github page provides the complete coding for the thesis paper: "Machine Learning Approach for Clinical Early-Stage Alzheimer's Disease Prediction" authored by Junfan Chen. This is a partial fulfillment of the requirements for the degree requirement of Master of Biostatistics.

## Data Preprocessing
This thesis study is completed based on the OASIS-4 dataset provided at the courtesy of Open Access Series of Imaging Studies (OASIS) hosted by the Knight Alzheimer's Disease Research Center of Washington University (Knight ADRC). The origial dataset consist a total of 663 patients, which by adjusted for missingness, the final dataset sample size is given as a total of 628 patients.
Available at:https://sites.wustl.edu/oasisbrains/

## Machine Learning Model building
The machine learning models selected for this study were recruited from the previously conducted meta analysis: Random Forest, Decision Tree, XGBoost, Supported Vector Machine (SVM), Naïve Bayes, Ridge, and Lasso regression.

## Study Analysis
This study focuses on two parts of analysis. Part 1 of the analysis focus on the classification of AD patients from other neurodegenerative and recorded disease. Outcome labeled as 1 for AD patients, and 0 for the rest of the patients. Part 2 of the analysis focus on the classification of Early stage AD patients from other AD patients. Outcome labeled as 1 for Early stage AD patients, and 0 for the rest of AD patients.
The final data set is split into training and tesitng dataset by a 70%/30% ratio, where all 30 features have been included for the analysis.


# ML_fundamentals_2026

Repository for the AI - Machine Learning Foundations course (2026), 
IE University.
Prof. Metteo Turilli

## Assignment 1: Data Preparation and Feature Engineering

**Student:** Estelle Arnander  
**Date:** 3rd March 2026

### Overview
This notebook provides a full data preparation and feature engineering process
for the UCI Bank Marketing dataset. The main goal
is to predict if a client will subscribe to a term deposit
after a telemarketing campaign.

### Pipeline Structure
0. Task ordering 
1. Prediction target identification
2. Data loading and exploratory analysis
3. Stratified data splitting 
4. Missing value handling
5. Categorical variable encoding (ordinal and one-hot)
6. Feature scaling (StandardScaler)
7. Feature selection (correlation and VIF analysis)
8. Class imbalance handling (Random Oversampling)
9. Logistic Regression training and evaluation
10. Final Comments

### Requirements

pandas
numpy
matplotlib
seaborn
scikit-learn
imbalanced-learn
statsmodels

### How to Run
1. Download the dataset from Kaggle: 
   https://www.kaggle.com/datasets/captaintyping/uci-bank-marketing-dataset/data
   and place `bank-additional.csv` in the same directory as the notebook
   (Or download it from the GitHub Repository)
2. Download `assignment_1_estelle_arnander.ipynb`
3. Open the file in a Jupyter Notebook environment 
   (e.g. PyCharm, Google Colab, JupyterLab)
4. Select *Restart Kernel and Run All* to execute the full pipeline


### Bibliography

'Burkov, A. (2020). Machine Learning Engineering. 
True Positive Inc. ISBN 9781999579579.'

Turilli, M. (2026). AI: Machine Learning Foundations, 
Lectures 1–12 [Course slides]. IE University.

Moro, S., Cortez, P., & Rita, P. (2014). A data-driven approach 
to predict the success of bank telemarketing. Decision Support 
Systems, 62, 22–31. https://doi.org/10.1016/j.dss.2014.03.001
[Original paper describing the UCI Bank Marketing dataset]

Chawla, N. V., Bowyer, K. W., Hall, L. O., & Kegelmeyer, W. P. 
(2002). SMOTE: Synthetic Minority Over-sampling Technique. 
Journal of Artificial Intelligence Research, 16, 321–357.
https://doi.org/10.1613/jair.953

scikit-learn developers. (2024). scikit-learn: Machine Learning 
in Python. https://scikit-learn.org
[Used for implementation of StandardScaler, OneHotEncoder, 
OrdinalEncoder, LogisticRegression, and VarianceThreshold]

Anthropic. (2026). Claude (claude-sonnet-4-6) [Large language 
model]. https://www.anthropic.com

----------------------------

For this project, as listed in the Bibilography, I used Claude (Anthropic). 

* Code Troubleshooting: I asked Claude to help me find logic errors and fix syntax issues in the code.
* Peer Review: Once I finished the first draft, I had the model review my arguments and methods. This helped me find gaps in my reasoning and strengthen my conclusions.
* Formative Feedback: I turned to Claude for ongoing feedback and suggestions to improve the clarity, flow, and structure of the text documentation when it was lacking.

While Claude provided suggestions and technical help, I reviewed, edited, and approved all final decisions, code, and written conclusions to ensure everything was accurate and original.


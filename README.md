# Heart Disease Prediction using Machine Learning Approach

## About heart disease
Heart Disease (including Coronary Heart Disease, Hypertension, and Stroke) remains the No. 1 cause of death in the US.The Heart Disease and Stroke Statistics—2019 Update from the American Heart Association indicates that:

- 116.4 million, or 46% of US adults are estimated to have hypertension. These are findings related to the new 2017 Hypertension Clinical Practice Guidelines.
- On average, someone dies of CVD every 38 seconds. About 2,303 deaths from CVD each day, based on 2016 data.
- On average, someone dies of a stroke every 3.70 minutes. About 389.4 deaths from stroke each day, based on 2016 data.

## Project Overview
In this notebook I will try to unleash useful insights using this heart disease datasets and by building stacked ensemble model by combining the power of best performing machine learning algorithms.

Table of Content of this notebook:

1. Data description
2. Importing Libraries & setting up environment
3. Loading dataset
4. Data Cleaning & Preprocessing
5. Exploratory Data Analysis
6. Outlier Detection & Removal
7. Training & Test Split
8. Cross Validation
9. Model Building
10. Model evaluation & comparison
11. Feature Selection
12. Model Evaluation
13. Conclusion

## About Data
Dataset is ontained from "heart statlog cleveland hungary" which is curated by combining 5 popular heart disease dataset namely from, Cleveland, Hungarian, Switzerland, Long Beach VA and Statlog (Heart) dataset.

This dataset consists of 11 features and a target variable. It has 6 nominal variables and 5 numeric variables. The detailed description of all the features are as follows:

1. Age: Patients Age in years (Numeric)
2. Sex: Gender of patient (Male - 1, Female - 0) (Nominal)
3. Chest Pain Type: Type of chest pain experienced by patient categorized into 1 typical, 2 typical angina, 3 non-anginal pain, 4 asymptomatic (Nominal)
4. resting bp s: Level of blood pressure at resting mode in mm/HG (Numerical)
5. cholestrol: Serum cholestrol in mg/dl (Numeric)
6. fasting blood sugar: Blood sugar levels on fasting > 120 mg/dl represents as 1 in case of true and 0 as false (Nominal)
7. resting ecg: Result of electrocardiogram while at rest are represented in 3 distinct values 0 : Normal 1: Abnormality in ST-T wave 2: Left ventricular hypertrophy (Nominal)
8. max heart rate: Maximum heart rate achieved (Numeric)
9. exercise angina: Angina induced by exercise 0 depicting NO 1 depicting Yes (Nominal)
10. oldpeak: Exercise induced ST-depression in comparison with the state of rest (Numeric)
11. ST slope: ST segment measured in terms of slope during peak exercise 0: Normal 1: Upsloping 2: Flat 3: Downsloping (Nominal)

### Target Variable
12. target: It is the target variable which we have to predict 1 means patient is suffering from heart risk and 0 means patient is normal.

## Installations
This project requires Python 3.x and the following Python libraries should be installed to get the project started:

- [Numpy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [scikit-learn](https://scikit-learn.org/stable/)
- [seaborn](https://seaborn.pydata.org/installing.html)
- [xgboost](https://xgboost.readthedocs.io/en/latest/build.html)

I also reccommend to install Anaconda, a pre-packaged Python distribution that contains all of the necessary libraries and software for this project which also include jupyter notebook to run and execute [IPython Notebook](https://ipython.org/notebook.html).

## Code
Actual code to get started with the project is provided is in `heart-disease-classification.ipynb`.

## Run
In a terminal or command window, navigate to the top-level project directory and run one of the following commands:
`ipython notebook heart-disease-prediction.ipynb` or

`jupyter notebook heart-disease-prediction.ipynb`

This will open the Jupyter Notebook software and project file in your browser.

## Model Evaluation
I have done model evaluation based on following sklearn metric.

1. [Cross Validation Score](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.cross_val_score.html)
2. [Confusion Matrix](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.confusion_matrix.html)
3. [Plotting ROC-AUC Curve](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.roc_curve.html)
4. [Plotting Precision recall Curve](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.precision_recall_curve.html)
5. [Sensitivity and Specitivity](https://en.wikipedia.org/wiki/Sensitivity_and_specificity)
6. [Classification Error](https://www.dataschool.io/simple-guide-to-confusion-matrix-terminology/)
7. [Log Loss](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.log_loss.html)
8. [Mathew Correlation coefficient](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.matthews_corrcoef.html)

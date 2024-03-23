# US-Adult-Census-1996
# US Adult Census Income Dataset - Machine Learning Analysis

## Description
This repository contains a machine learning analysis of the US Adult Census Income Dataset from the UCI Machine Learning Repository. The dataset contains demographic and employment-related information collected from the 1994 US Census. The goal of this analysis is to build and evaluate machine learning models for predicting whether an individual's annual income exceeds $50,000 based on various features.

## Dataset
The US Adult Census Income Dataset consists of the following features:

1. **age**: Continuous.
2. **workclass**: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.
3. **fnlwgt**: Final weight. This is a continuous feature.
4. **education**: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.
5. **education-num**: Continuous.
6. **marital-status**: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.
7. **occupation**: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.
8. **relationship**: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.
9. **race**: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.
10. **sex**: Female, Male.
11. **capital-gain**: Continuous.
12. **capital-loss**: Continuous.
13. **hours-per-week**: Continuous.
14. **native-country**: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.
15. **income**: >50K, <=50K.

The target variable is **income**, which indicates whether an individual's annual income exceeds $50,000 (>50K) or not (<=50K).

## Analysis
In this repository, we perform the following steps:

1. **Data Preprocessing**: The dataset is cleaned and prepared for analysis. This includes handling missing values, encoding categorical variables, and splitting the data into training and testing sets.

2. **Exploratory Data Analysis (EDA)**: We explore the dataset to gain insights into the relationships between different features and the target variable. This includes visualizations and statistical summaries.

3. **Feature Selection**: We investigate the importance of different features and select the most relevant ones for building the machine learning models.

4. **Model Training and Evaluation**: Various machine learning algorithms are trained and evaluated on the dataset. This includes techniques such as logistic regression, decision trees, random forests, and gradient boosting. Model performance is assessed using appropriate evaluation metrics, such as accuracy, precision, recall, and F1-score.

5. **Model Optimization**: We tune the hyperparameters of the best-performing models to improve their performance further.

6. **Model Deployment**: The final optimized model(s) are saved and can be deployed for making predictions on new data.

## Results
The results of the analysis, including the performance of different models, feature importances, and any notable findings, are documented in the `results.ipynb` file.

## Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.


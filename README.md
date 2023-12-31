# Predicting Health Insurance Charges: Unraveling Cost Determinants through Machine Learning 🌡️💸

**Note: For the best viewing experience of the Jupyter Notebook, please use this [nbviewer link](https://nbviewer.org/github/FutureGoose/predicting_insurance_charges/blob/main/medical_cost_reg_ver2.ipynb).**

## Table of Contents 📘
1. [Introduction](#Introduction-)
2. [Dataset Overview](#Dataset-Overview-)
3. [Data Preprocessing](#Data-Preprocessing-)
4. [Exploratory Data Analysis](#Exploratory-Data-Analysis-)
5. [Feature Engineering](#Feature-Engineering-)
6. [Model Training and Selection](#Model-Training-and-Selection-)
7. [Hyperparameter Optimization](#Hyperparameter-Optimization-)
8. [Model Evaluation](#Model-Evaluation-)
9. [Key Findings and Insights](#Key-Findings-and-Insights-)
10. [Conclusion](#Conclusion-)

<a name="Introduction-"></a>
## 1. Introduction 🌟
This repository serves as a comprehensive guide to predicting health insurance charges through a machine learning lens. Drawing inspiration from demographic and health-related factors, the project seeks not just to predict but also to unravel the intricate weave of variables that govern healthcare costs. 

Our primary aim, grounded in Supervised Learning, revolves around Regression, using models such as Random Forest Regressor and XGBRegressor. We harness metrics like RMSE, MAE, and R-squared value to assess model accuracy. Yet, our vision goes beyond mere numbers; we aspire to shed light on the nuanced relationships influencing these charges. Through this analysis, we hope to offer meaningful insights, beneficial for both insurance companies and individuals, encapsulating our mission: **"To use personal information to accurately and insightfully predict healthcare costs."**

<a name="Dataset-Overview-"></a>
## 2. Dataset Overview 📁
The dataset used for this project consists of health insurance details of individuals, including demographics, smoking habits, body mass index, number of children, region, and corresponding charges. With this comprehensive data, the project aims to draw correlations and patterns influencing insurance prices.

<a name="Data-Preprocessing-"></a>
## 3. Data Preprocessing 🧹
Data preprocessing involved handling missing values, converting categorical variables into numerical formats, and ensuring the dataset is optimized for machine learning models.

<a name="Exploratory-Data-Analysis-"></a>
## 4. Exploratory Data Analysis 📊
Detailed EDA was performed to understand the dataset's structure, unearth patterns, identify outliers, and ascertain potential variables affecting the insurance charges.

<a name="Feature-Engineering-"></a>
## 5. Feature Engineering ⚙️
Strategic feature engineering techniques were employed to harness the data's full potential. This involved creating interaction terms, binning, and encoding categorical features to ensure the dataset is primed for predictions.

<a name="Model-Training-and-Selection-"></a>
## 6. Model Training and Selection 🤖
Multiple models, including Linear Regression, Random Forest, XGBoost, CatBoostRegressor and Support Vector Machines, were trained. Their performance metrics were compared to select the best fit for the prediction task.

<a name="Hyperparameter-Optimization-"></a>
## 7. Hyperparameter Optimization 🔧
To ensure the models perform optimally, hyperparameters were fine-tuned using GridSearchCV, resulting in improved predictive performance.

<a name="Model-Evaluation-"></a>
## 8. Model Evaluation 🎯
The final model's performance was gauged using various metrics, including RMSE, MAE, and R-squared, providing a holistic evaluation of its efficacy.

<a name="Key-Findings-and-Insights-"></a>
## 9. Key Findings and Insights 💡
Insights drawn from the model emphasized the importance of certain variables, such as smoking habits, BMI, and age, in determining insurance costs. Detailed interpretations have been provided to understand the magnitude and direction of these impacts.

<a name="Conclusion-"></a>
## 10. Conclusion 🎉
The project illuminated various hidden determinants of health insurance charges. By harnessing machine learning, I derived actionable insights, paving the way for both consumers and insurance providers to make informed decisions.

---
## Getting Started 🏁
For an optimal viewing experience of the Jupyter Notebook, use the following nbviewer link:
[View Notebook on nbviewer](https://nbviewer.org/github/FutureGoose/predicting_insurance_charges/blob/main/medical_cost_reg_ver2.ipynb)

This link provides a superior rendering compared to the default GitHub file viewer.

### Prerequisites 📋
For successful execution, you'll need:
- Python 3.x
- Jupyter Notebook
- Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-Learn

### Installing 🛠️
1. Clone this repository.
2. Install the required libraries.
3. Navigate to and open the Jupyter Notebook.

Your constructive feedback and queries are always welcome!

---
## Acknowledgments 🙏
A huge thanks to the data science community for their continuous efforts in making datasets available for public use and promoting an environment of collective learning.

## License 📄
This project is licensed under the MIT License. Refer to the LICENSE.md file for detailed information.

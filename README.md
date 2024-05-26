# Credit Risk Prediction Model

_Created by Fitria Dwi Wulandari – August, 2022_

### **Project Background**
XYZ Company operates in the lending industry. In the lending industry, making decisions about loan approvals is crucial. When a lending company receives a loan application, it must assess the applicant's profile to determine if they are likely to repay the loan. Approving a loan to an applicant who is unlikely to repay it can lead to significant financial losses for the company. Conversely, rejecting a loan application from an applicant who is likely to repay it results in missed business opportunities. Therefore, identifying and minimizing bad-risk loans is essential to mitigate financial losses and maintain business profitability.

### **Objectives**
This project aims to minimize the approval of bad-risk loans by:
* Identifying patterns that indicate a high likelihood of loan default (bad risk).
* Developing predictive models to assess the credit risk of loan applicants.

### **Methodology**
#### <code style="color : darkpurple">Data Preparation</code>
* **Source**: Data obtained from the ID/X Partners Data Scientist Virtual Internship Program at Rakamin Academy.
* **Actions**: Cleaning and preparing the data for analysis, ensuring data quality and consistency.
  
#### <code style="color : darkpurple">Exploratory Data Analysis (EDA)</code>
* **Purpose**: Discover patterns, spot anomalies, and gain a deeper understanding of the data's characteristics.

#### <code style="color : darkpurple">Machine Learning</code>
* **Approach**: Building predictive models to assess credit risk.
* **Algorithms Tested**: Eight different algorithms were evaluated to determine the best model for credit risk prediction.

#### <code style="color : darkpurple">Tools</code>
* **Programming Language**: Python.
* **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.

### **Results**
* The analysis identified key factors influencing loan repayment likelihood: last payment month, last payment amount, principal amount received, recovery value, and last payment year.
* The Random Forest model, with an accuracy of 99%, was the most effective in predicting credit risk. This model enables precise and reliable decision-making, significantly reducing the likelihood of granting loans to bad-risk applicants and thereby minimizing financial losses.

### **Future Work**
* **Model Improvement**: Further hypertuning the models and exploring advanced algorithms to improve performance.
* **Extended Analysis**: Include additional data sources and variables for a more comprehensive understanding of credit risk factors.

### Repository Contents
* [**Script**](https://github.com/fitria-dwi/Credit-Risk-Prediction/blob/main/Credit%20Risk%20Prediction.ipynb): Python scripts for data preprocessing, cleaning, and model training.
* [**Report Deck**](https://github.com/fitria-dwi/Credit-Risk-Prediction/blob/main/Credit%20Risk%20Prediction%20Presentation.pdf): Detailed reports on findings, including insights and model performance metrics.

# Credit Risk Prediction

Created by Fitria Dwi Wulandari – August, 2022

#### <ins>**Project Background**</ins>
The company operates in the lending industry. When a lending company receives a loan application, it must decide whether to approve or reject the application based on the applicant’s profile. If the applicant is likely to repay the loan, rejecting the application will result in business losses for the company. This situation is referred to as a good risk. Conversely, if the applicant is unlikely to repay the loan, approving the application will lead to financial losses for the company. This scenario is known as a bad risk.

Granting loans to bad-risk applicants is the largest source of financial loss. Credit loss represents the amount of money lost by the lender when the applicant defaults on the loan or absconds with the borrowed funds.

#### <ins>**Objectives**</ins>
1. Identified patterns that indicate if a person is unlikely to repay the loan or labeled as a bad risk so that it can be used to take action such as rejecting the loan, reducing the amount of loan, lending at a higher interest rate, etc.
2. Implemented machine learning algorithms to build predictive models so that the company can automatically predict whether the loan application submitted by the applicant will be labeled as a bad risk or not. With this, the company can make a decision to approve or reject the loan application.

#### <ins>**Methodology**</ins>
* **Data Preparation**: data obtained from Kaggle.
* **Exploratory Data Analysis**: process to discover patterns, spot anomalies, and gain a deeper understanding of the data's characteristics.
* **Machine Learning**: build predictive models to predict customer response to the next marketing campaign. 8 algorithms were tried and then evaluated to determine the best algorithm for the prediction model.

#### <ins>**Results**</ins>
1. The most important feature in determining whether the applicant has the possibility of not repaying the loan is the last payment month, the last payment amount, the principal amount received, the recovery value, and the last payment year.
2. The best model to predict the risk status of loan applications is Random Forest, with an accuracy value of 99%.

#### <ins>**Tools**</ins>
Python.

#### <ins>**Skill Sets**</ins>
Data Cleaning, Exploratory Data Analysis, Data Visualization, Data Analysis, Machine Learning, Predictive Modeling.

#### <ins>**Documentation**</ins>
* **Presentation Deck**: [cr-prediction deck](https://github.com/fitria-dwi/Credit-Risk-Prediction/blob/main/Credit%20Risk%20Prediction%20Presentation.pdf)
* **Script Python**: [cr-prediction deck](https://github.com/fitria-dwi/Credit-Risk-Prediction/blob/main/Credit%20Risk%20Prediction.ipynb)

#### **References**:
- https://www.investopedia.com/terms/g/grace_period.asp
- https://www.investopedia.com/terms/d/default2.asp
- https://www.valuepenguin.com/loans/what-does-it-mean-to-default-on-a-loan
- https://www.bankrate.com/personal-finance/debt/charged-off-as-bad-debt/#:~:text=If%20you've%20been%20delinquent,a%20loss%20for%20the%20company.
- https://www.investopedia.com/terms/c/chargeoff.asp

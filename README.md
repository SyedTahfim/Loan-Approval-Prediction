## <img src="https://cdn-icons-png.flaticon.com/128/3989/3989573.png" width="20" /> Motivation
Banks and lenders need to minimize defaults and non-performing loans. Accurate prediction models help identify applicants who are likely to repay, protecting the institution's capital and maintaining portfolio health. Even a small improvement in prediction accuracy can translate to millions in saved losses. 
<p align="center">
    <img src="https://inception-app-prod.s3.amazonaws.com/OTg3NWIzOGQtOGU3YS00OTY2LTlkNzktZDZmMTNmN2NlMGNl/content/2017/11/loan-approved.gif" width="45%" alt="Image 1 Description" style="float: left; margin-right: 2%;">
</p>

## <img src="https://cdn-icons-png.flaticon.com/128/3176/3176324.png" width="20" /> Feaatures
- Data Wrangling
- Exploratory Data Analysis
    -  Distribution of Numerical Variables
    -  Correlation between the Numerical Variables
    -  Correlation with the Loan Amount
    -  Correlationwith the Income
 <p align="center">
    <img src="https://github.com/SyedTahfim/Loan-Approval-Prediction/blob/main/distribution_numerical.png" width="45%" alt="Image 1 Description" style="float: left; margin-right: 2%;">
 </p>
 
- Identify Degree of Multicollinearity
- Feature Engineering using Weight of Evidence (WOE) and Information Value (IV)
- Logistic Regression Model Implementation using Scikit Learn Library
- Model Stability Test 

## <img src="https://cdn-icons-png.flaticon.com/128/18289/18289400.png" width=20 /> Dataset
-  __Title__: Loan Approval/Rejection Data
-  __Dataset Size__: 4269
-  __Target Variable__: Approved and Rejected

## <img src="https://cdn-icons-png.flaticon.com/128/6259/6259277.png" width=20 /> Libraries
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Sci-kit Learn
- Statistical Models

## <img src="https://cdn-icons-png.flaticon.com/128/1844/1844921.png" width=20 /> Evaluation Metrices
- Accuracy
- ROC AUC Score
- PSI (Population Stability Index)

## <img src="https://cdn-icons-png.flaticon.com/128/9623/9623606.png" width=20 /> Insights
<p align="center">
    <img src="https://github.com/casper6020/Loan-Approval-Prediction/blob/main/Loan%20Approval%20Prediction_Log_Report.png" width="45%" alt="Image 1 Description" style="float: left; margin-right: 2%;">
</p>

**CIBIL Score (β = 0.0123, p < 0.001):**
*The positive and statistically significant coefficient suggests that a higher CIBIL score increases the log-odds of loan approval. This aligns with standard credit risk practices, where applicants with higher credit scores are considered more creditworthy and thus more likely to be approved.*

**Loan Term (β = -0.1657, p < 0.001):**
*The negative coefficient implies that longer loan tenures reduce the log-odds of loan approval. Longer repayment periods often increase the lender’s risk exposure, as they are more uncertain and subject to future financial changes of the borrower. Therefore, this negative relationship is financially consistent.*

**Loan-to-Income Ratio (β = -1.4561, p < 0.001):**
*A higher loan-to-income ratio significantly reduces the likelihood of loan approval. This indicates that when the loan amount is large relative to income, the applicant is perceived as riskier, consistent with prudent credit assessment principles.*



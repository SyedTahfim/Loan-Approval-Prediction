## <img src="https://cdn-icons-png.flaticon.com/128/3989/3989573.png" width="20" /> Motivation
Banks and lenders need to minimize defaults and non-performing loans. Accurate prediction models help identify applicants who are likely to repay, protecting the institution's capital and maintaining portfolio health. Even a small improvement in prediction accuracy can translate to millions in saved losses. 
<p align="center">
    <img src="https://inception-app-prod.s3.amazonaws.com/OTg3NWIzOGQtOGU3YS00OTY2LTlkNzktZDZmMTNmN2NlMGNl/content/2017/11/loan-approved.gif" width="45%" alt="Image 1 Description" style="float: left; margin-right: 2%;">
</p>

## <img src="https://cdn-icons-png.flaticon.com/128/3176/3176324.png" width="20" /> Features
- Data Wrangling
- Exploratory Data Analysis
    -  Distribution of Numerical Variables
    -  Correlation between the Numerical Variables
    -  Correlation with the Loan Amount
    -  Correlation with the Income
 <p align="center">
    <img src="https://github.com/SyedTahfim/Loan-Approval-Prediction/blob/main/distribution_numerical.png" width="45%" alt="Image 1 Description" style="float: left; margin-right: 2%;">
 </p>
 
- Identify Degree of Multicollinearity
- Feature Engineering using Weight of Evidence (WOE) and Information Value (IV)
- Logistic Regression Model Implementation using Sci-kit Learn Library
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

## <img src="https://cdn-icons-png.flaticon.com/128/1844/1844921.png" width=20 /> Model Evaluation
- The logistic regression model achieved an accuracy score of __91.33%__. On imbalance datasets, the accuracy scores are generally high because the model gets biased towards the negative class. 
- The ROC curve and AUC score usually reveal the true performance of the model trained on imbalance dataset. A ROC curve in the top-left corner of the plot is an indication that the model can separate the two classes distinctively at different threshold.
- The model achieved an AUC score of 97.33%, which indicates the __True Positive Rate (TPR)__ remains very high without increasing the __False Positive Rate (FPR)__. 

<p align="center">
    <img src="https://github.com/SyedTahfim/Loan-Approval-Prediction/blob/main/ROC_AUC_Score.png" width="45%" alt="Image 1 Description" style="float: left; margin-right: 2%;">
</p>

- PSI (Population Stability Index) value was __0.0042__. This means the probability distribution in the test data is almost the same as the training data. 

## <img src="https://cdn-icons-png.flaticon.com/128/9623/9623606.png" width=20 /> Key Takeaways
<p align="center">
    <img src="https://github.com/casper6020/Loan-Approval-Prediction/blob/main/Loan%20Approval%20Prediction_Log_Report.png" width="45%" alt="Image 1 Description" style="float: left; margin-right: 2%;">
</p>

**CIBIL Score (β = 0.0123, p < 0.001):**
*The positive and statistically significant coefficient suggests that a higher CIBIL score increases the log-odds of loan approval. This aligns with standard credit risk practices, where applicants with higher credit scores are considered more creditworthy and thus more likely to be approved.*

**Loan Term (β = -0.1657, p < 0.001):**
*The negative coefficient implies that longer loan tenures reduce the log-odds of loan approval. Longer repayment periods often increase the lender’s risk exposure, as they are more uncertain and subject to future financial changes of the borrower. Therefore, this negative relationship is financially consistent.*

**Loan-to-Income Ratio (β = -1.4561, p < 0.001):**
*A higher loan-to-income ratio significantly reduces the likelihood of loan approval. This indicates that when the loan amount is large relative to income, the applicant is perceived as riskier, consistent with prudent credit assessment principles.* 

## <img src="https://cdn-icons-png.flaticon.com/128/9506/9506312.png" width=20 /> Business Insight
Given the logistic regression results, we can conclude that the credit analyst should approve loan applications where the applicant has higher CIBIL score, the loan term is not too long, and the loan to income ratio within the risk appetite of the institutions. 





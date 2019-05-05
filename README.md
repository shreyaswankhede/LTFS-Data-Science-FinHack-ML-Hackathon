# LTFS-Data-Science-FinHack-ML-Hackathon
The objective of this project is to predict the probability of loanee or borrower defaulting on a vehicle loan in the first EMI (Equated Monthly Instalments) on the due date. 

<h3>Vehicle Loan Default Prediction </h3>
<h5>What’s Loan Default Prediction ? & What’s the problem?</h5>
<p>Vehicle loan default happens when a customer fails to make the agreed loan payments to the lender or financial services that lent the money for its purchase within particular time period.If a person is default on car loan payments, the lender may take action to repossess the vehicle for selling it.
Default of vehicle loans can badly affect credit scores of borrowers.
Financial institutions incur significant losses due to the default of vehicle loans.
Loan Default Prediction ensures that whether clients are capable of repayment or not and important determinants can be identified which can be further used for minimising the default rates.</p> 

 <h5>Objective</h5>
 <p>End-user: Financial institution</p>

Objective: The objective of this project is to predict the probability of loanee or borrower defaulting on a vehicle loan in the first EMI(Equated Monthly Instalments) on the due date.   

Dataset: The Vehicle Loan Default Prediction dataset includes following features:
         Dependent feature: loan_default
         Independent features: disbursed_amount, asset_cost, ltv, PERFORM_CNS.SCORE etc.
The dataset contains 345550 rows and 41 features.

<h5>Data Loading and Cleaning</h5>
<p>Combining training and testing data.
<p>Checking missing values in data. 
<p>Imputing Employment.<p>Type missing values with 'Self employed' values.
<p>Checking the outliers using boxplot.
<p>Removing the outliers of 'disbursed_amount' & 'asset_cost' features</p>

 <h5>Data Analysis and Visualization</h5>
 <p> Check the images provided in the code Section.
	
 <h5> Feature Enginnering & Feature Selection</h5>	
 <p>Calculating Age column using 'Date.of.Birth'.
Calculating 'AVERAGE.ACCT.AGE' and 'CREDIT.HISTORY.LENGTH' in months.
Creating bins of PERFORM_CNS.SCORE and LTV.
Replacing Values of PERFORM_CNS.SCORE.DESCRIPTION.
Generating New Features like 'ACTIVE.ACCTS','CURRENT.BALANCE' etc.
Dropping irrelevant columns like 'DisbursalDate', 'Current_pincode_ID' ,'NO.OF_INQUIRIES' etc.
	
 <h5> Model Building & Result </h5>
 <p>CatBoost Classifier	
 <p>ROC AUC Score  0.6442


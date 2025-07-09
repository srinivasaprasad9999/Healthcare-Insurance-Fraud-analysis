# Healthcare-Insurance-Fraud-analysis
## Problem Statement:
The goal is to do an Exploratory data analysis (EDA) to discover important variables helpful in detecting the behaviour of potentially fraudulent insurance providers. This will help in identifying the suspicious behaviour of future claims by the providers. 

## DataSet:
<a href ="https://s3.ap-south-1.amazonaws.com/new-assets.ccbp.in/frontend/content/data-analytics/Datasets_DA_Track/DA_Capstone_3_Dataset.zip"> DataSet_files</a>

## Project_Report_pdf:
<a href="file:///C:/Users/srini/AppData/Local/Temp/Power%20BI%20Desktop/print-job-c65402ff-3475-4d4c-906f-73ed88800672/Healthcare%20Insurance%20Fraud%20analysis.pdf"> file:///C:/Users/srini/AppData/Local/Temp/Power%20BI%20Desktop/print-job-c65402ff-3475-4d4c-906f-73ed88800672/Healthcare%20Insurance%20Fraud%20analysis.pdf </a>

## Questions related to report:
Whether the number of male beneficiaries were higher than female beneficiaries in general and also in each race?

Whether the total reimbursements to the in-patients were higher than that made to the out-patients?

Is the number of in-patient beneficiaries much smaller than the number of out-patient beneficiaries?

Which state (coded number) had the highest number of beneficiaries?

How much percent of the beneficiaries were alive (Yes, you need to calculate it!) according to the latest entry on the data?

Which racial (coded number) background people had the highest number of beneficiaries?

What was the percentage of beneficiaries with heart failure as well as renal failure (kidney failure)

How many physician's identifiers were there in the dataset?

Which age group (calculate age at the time of hospitalization) gets hospitalized the most frequently?

Which age group benefits the most from the medi-care during hospitalization?

Why does the 66 to 90 age group get more benefits?

Does the onset of increase in hospitalization correlates with the retirement age of 65 years?

What was the relationship between hospitalization duration and the average amount claimed for reimbursement

What was the most occuring hospitalization duration?

What was the most common admit diagnosis code?

## Fraud specific questions:
What percentage of providers were marked as potentially fraudulent?

How much money was reimbursed by potentially fraudulent insurance providers?

Which potentially fraudulent provider has reimbursed the most amount of money in IP and OP?

Can all the claims reimbursed by a given potentially fraudulent insurance provider be marked as fraudulent?

## Focused on In Patient data:
For In Patients Claims, how much percentage of claims had Attending physician the same as Operating physician? (Hint: Considering handling NA values also)

For In Patients Claims, how much percentage of claims had Attending physician the same as Other physician? (Hint: Considering handling NA values also)

For In Patients Claims, how much percentage of claims had an Attending physician same as Operating as well as Other physician? (Hint: Considering handling NA values also)

Does the "likelihood" of number of "potentially" fraudulent claims reduce with increasing no of physicians involved with an in-patient?

What is the "likelihood" of "potentially" fraudulent claim when two different physicians are involved (operating or other) with an in-patient?

What is the "likelihood" of "potentially" fraudulent claim when three different physicians are involved (operating or other) with an in-patient?

Whether the patients in the age bracket of 66-90 got hospitalized for a longer duration in case of claims reimbursed by "potentially" fraudulent providers?

Which physician is associated with the highest number of claims made with respect to in-patients data, who is solely associated with "potentially" fraudulent providers?

Is there an anomalous amount in the reimbursement claim filed by beneficiaries with respect to in-patients data, which raises your suspicion?

## Focused on Out Patient data:
Which physician is associated with the highest number of claims made with respect to out-patients data, who is solely associated with "potentially" fraudulent providers?

Is there an anomalous amount in the reimbursement claim filed by beneficiaries with respect to out-patients data, which raises your suspicion?

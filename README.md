# Risk Analysis
> Finding factors that effect loan defaulting for a consumer finance company


<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement
You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

 

The data given below contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
![image](https://github.com/susrutha-chowdary/CaseStudy1/assets/87435569/3ef9847f-c617-4dad-9a74-b976723d427a)

When a person applies for a loan, there are two types of decisions that could be taken by the company:

Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

## Conclusions
- Dti is found to be higher for defaulters than for fully paid users.
- grade A has very less chance of defaulting where as grades C,D,E,F have comparatively higher chances of defaulting.
- Loans with 60 months as term have higher defaulting rate than loans with 30 months.



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->



## Contributers
- Surutha.K 
- Abhishek Raghuvanshi

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

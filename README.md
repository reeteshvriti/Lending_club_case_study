# Project Name: Lending club Case study
> 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.

This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 
Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 

- What is the background of your project?
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

- What is the business probem that your project is trying to solve?

You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

- What is the dataset that is being used?

The dataset we're utilizing for our loan analysis is likely a historical loan data repository. This dataset would contain information about previous customers, including:

Demographic data: Age, gender, occupation, and location.
Financial information: Income, credit history, debt-to-income ratio, and existing loans.
Loan application details: Loan amount, interest rate, loan term, and collateral.
Repayment history: On-time payments, missed payments, and default status.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- As the salary increases the loan amount also gets increased.
- People who are staying in the rental house are having more number of loans.
- People whose salary was ranging more than 80k was opting for more loan amount.
- Majority of the people purchased the loan because of debit_consolidation.
- People whose salary is less than 40k has more chances of getting defaulted and the people whose salary is and more than 80k and above has less chances of getting defaulted or getting charged off.
- People who had took the loan for small busniess is more likely to get charged off.
- People who has more intrest rate has more chances of getting charged off compared to others.
- People who has a very high DTI are morelikely to get charged off.
- People having 2 bankruptcies are more likely to get charged off.
- State address TN has more number of charged off loans.
- people who took the loan in 2007 has more charged off .
- G grade loan has more number of charged off loans. 


- From the above cluster map we can conclude
- Positive correleation
Term has postive correleation with intrest rate
fundex amount inv has strong correleation with loan amount
Loan amount has strong correleation with funded amount
- Negative Correleation
Bank ruptcies has weak correleation with funded amount inv, loan amount and funded amount
intrest rate has a weak correleation with annual income
DTI has weak correleation with annual income
Employee length has weak correleation with intrest rate

 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - Numpy
- library - Pandas
- library - Seaborn, Matplotlib



## Contact
Created by [@reeteshvriti]
-  [reetesh-v.netlify.app]- feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
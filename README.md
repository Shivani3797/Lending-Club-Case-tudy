# Lending-Club-Case-Study
We are provided a loan dataset and the following are the objectives of the case study
1. Finding risky borrowers, those who default cause the largest amount of loss to the lenders. In this case, the customers labeled as 'charged-off' are the 'defaulters'.
2. Understanding the driving factors (or driver variables) behind loan default, i.e. the variables that are strong indicators of default.


## Table of Contents
The code proceeded in the following manner:
1. Data Understanding
2. Data Cleaning and Manipulation
3. Data Analysis
     (i) Univariate Analysis
     (ii) Bivariate Analysis
     (iii) Correlation Ana]alysis
## General Information
PROBLEM STATEMENT
We have two situations,
(i) LOAN ACCEPTED: If the company approves the loan, there are 3 possible scenarios described below:
  1.Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
  
  2.Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
  
  3.Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan

(ii)Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset).

OBJECTIVES OF THE CASE STUDY

Finding risky borrowers, those who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.
Understanding the driving factors (or driver variables) behind loan default, i.e. the variables that are strong indicators of default.

## Conclusions
(i) Univariate Analysis:
  1. The majority of borrowers are renters.
2. The highest number of loans were issued in December.
3. The majority of loans were issued in the year 2011.
4. Most borrowers do not have a record of bankruptcy.
5. The average DTI for borrowers is 13.44.
6. Borrowers from California have the highest DTI.
7. Most customers borrow for debt consolidation.
8. The proportion of charged-off or defaulting borrowers is very low compared to fully paid borrowers.
9. The average annual income of borrowers is $65,939.46, with a maximum recorded income of $235,000.
10. The majority of borrowers are not verified by lenders.
11. The highest number of borrowers have been employed for 10 years.
12. A4 is the highest recorded sub-grade, while B is the highest recorded grade.
13. The average interest rate is 11.94%.

(ii) Segmented Univariate Analysis observation:
 1. Even though borrowers often take out loans for debt consolidation, most have already repaid them in full.
2. Individuals without homeownership do not have any defaulted borrowers.
3. Grade A employees rarely have risky borrowers and typically make timely loan payments.
4. Loans with a DTI ratio of 10-15 experience a higher rate of defaults.

(iii) Bivariate Analysis:
1. In the purpose vs. annual income plot, it is evident that applicants with higher salaries primarily sought loans for "home_improvement," "house," "renewable_energy," and "small_businesses."
2. Individuals with high annual incomes typically have homes under mortgage.
3. Borrowers opting for a 36-term loan exhibit a higher probability of fully repaying the borrowed amount.
4. Grade G shows the highest incidence of charge-offs.
5. Borrowers with annual incomes of 40k or less are more prone to being charged off.
6. The majority of charged-off borrowers are non-verified.
7. December stands out with the highest loan issuance and the greatest number of charged-off borrowers.
8. Borrowers facing higher interest rates and loan amounts are at an elevated risk of being charged off.


## Technologies Used
Pandas - version 1.3.4
NumPy - version 1.20.3
Seaborn - version 0.11.2
MatplotLib - version 3.4.3
Plotly - version 5.7.0

## Acknowledgements
Kunal Sahu Lending Club Case Study.
Shrenik Jain 100 days of machine learning.


## Contact
Created by [@Shivani3797] - feel free to contact me!




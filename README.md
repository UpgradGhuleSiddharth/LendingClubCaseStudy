# Lending Club Case Study
> In this case study, we use EDA for analysing risk in a consumer finance company which specialises in lending various types of loans. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- **Background**: We work for a consumer finance company which specialises in lending various types of loans to urban customers. This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. 

- **Aim**: Identify risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. 

- **Data**:We are given loan data for all loans issued through the time period 2007 t0 2011Since the loan was rejected, there is no transactional history of those applicants .with the company and so this data is not provided.There are 39,717 data points and 111 variables. loan_status is the target variable with following possible values:
  - Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
  - Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
  - Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

- **Approach**:

  ![image](https://user-images.githubusercontent.com/95560901/148832482-d3fed59d-cbbb-4222-9e2c-e7887124d29b.png)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Univariate analysis was quite useful to get familiar with data and understand its properties. It also helped us to identify outliers in the variables.
- The target variable in this analysis was a categorical variable. Hence, segmented univariate analysis and bivariate analysis contained essentially the same information.
- However, bivariate analysis was the most insightful for identifying driver variables that are indicators of default.
- We identified following 13 driver variables which are strong indicator of default: grade, sub_grade, pub_rec_bankruptcies, annual_inc, dti, int_rate, last_pymnt_amnt, loan_amnt, revol_bal, revol_util, total_pymnt, total_rec_late_fee


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Numpy - version 1.19.5
- Pandas - version 1.1.5
- Matplotlib - version 3.2.2
- Seaborn - version 0.11.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@siddharth-ghule-work-gmail] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

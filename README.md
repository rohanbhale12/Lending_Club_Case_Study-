# Lending Club Case Study
> This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.


## Table of Contents
* [General Info](#general-information)
* [Steps Involved](#steps-involved)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 
Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 

In this case study, we are analyzing complete loan data for all loans issued through the time period 2007 t0 2011.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Steps Involved
##### 1. Data Sourcing
##### 2. Data Cleaning and Transformations
##### 3. Univariate Analysis
##### 4. Bivariate
##### 5. Conclusions

## Conclusions
##### 1. We can see that almost 17% loans are charged off
##### 2. The charged off is more in RENT and MORTGAGE category compared to owned as these applicants are more
##### 3. Most of the borrowers taken loan for debt_consoldation and for credit card and thus charged off is also high for these purpose
##### 4. Charged off is more for 36 months compared to 60 months, the time taken to pay back the loan
##### 5. For Charged off- we can see that number of applicants are increasing from October to December every year, so the defaults occurred in those months
##### 6. We can see that the annual income less than 60k will be more chances of likely to default. Maximum likely to default are in 31-60 K range
##### 7. B grade is the highest grade who likely to default
##### 8. The interesting fact is those who have taken the loan between 6k-10k will  likely default
##### 9. Most of the applicants who likely to default are fall under 13-18 DTI ratio 
##### 10. Plot shows interest rate is increasing slowly with increase in year
##### 11. Charged Off's are getting increased with the grades and fully paid have higher income compared to Charged Off
##### 12. The interest rates are increasing with higher Debt to income Ratio with exceptions from the highest DTI group category


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy
- pandas
- matplotlib.pyplot
- seaborn
- warnings
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
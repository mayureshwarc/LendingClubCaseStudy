# Lending Club Case Study
> This project addresses data quality issues, performs necessary data transformations, and solves the business problem of identifying important driver variables for loan default. The analysis follows a clear structure, incorporating univariate and segmented univariate analysis, creating business-driven metrics, and conducting bivariate analysis to identify significant variable combinations. The project aims to provide meaningful insights for risk assessment and decision-making in the online loan marketplace.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
#### Background of the Project:
The project revolves around a consumer finance company specializing in lending various types of loans to urban customers. The company receives loan applications and makes decisions based on the applicant's profile. The project aims to use exploratory data analysis (EDA) to understand the influence of consumer attributes and loan attributes on the likelihood of loan default.

#### Business Problem:
The business problem this project is trying to solve is the identification of patterns and indicators that can help predict if a loan applicant is likely to default. By understanding the driving factors behind loan default, the company can take appropriate actions such as denying loans, reducing loan amounts, or charging higher interest rates to risky applicants. The goal is to minimize credit loss, which occurs when borrowers refuse to pay or default on their loans, by effectively assessing the risk of loan applicants.

#### Dataset Used:
We are using 'Loan Dataset' it contains the complete loan data for all loans issued through the time period 2007 to 2011.
The dataset used in this project contains information about past loan applicants, including their attributes and loan outcomes. It provides details about whether the applicants defaulted on their loans, paid them off in full, or are currently in the process of repaying.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Charged Off possibility increases with increase in loan amount. Around 25% for loan more than 28000. 
- Charged Off possibility increases with decrease in annual income.
- Close to 40% of Charged Off happen in month of January and July having maximum Debt to Income ratio (0.2+). It could be due to Festive season in December and Summer vacation in May-June.
- Individuals residing in rented or mortgaged houses are more prone to loan charge-offs, suggesting a higher risk associated with these housing arrangements.
- Majority of the loans are taken for the purpose of Debt Consolidation and it is 8th highest in term of Charged of percentage.
- Chances of Debt are observed to be more when loan taken for Small business, especially in state as TN, AK, MT and MS.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - version 1.21.3
- pandas - version 1.5.3
- matplotlib - version 3.4.3
- seaborn - version 0.12.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- The training provided by IIIT Bangalore greatly contributed to the successful execution of this project.
- This project was based on [this tutorial](https://learn.upgrad.com/course/4705).


## Contact
Created by [@Mayureshwarc]  - feel free to contact us!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

# Lending-Club-Case-Study


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The aim of this case study is to identify risky loan applicants using EDA, which the company can utilise for its portfolio and risk assessment. 
We will identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

The dataset used for this project is : loan.csv

## Conclusions
On the basis of the analysis made above, the most impactful drivers are :

<b>Univariate Factors</b>
<ul>
    <li>Higher interest rate</li>
<li>Term of the loan (60 months)</li>
<li>Loan purpose (small business, renewable energy, educational)</li>
<li>Higher revolving line utilization rate</li>
<li>Loan grade & sub-grade</li>
<li>Higher loan amount</li>
<li>Higher installment amount</li>
<li>Lower annual income</li>
<li>Higher debt to income ratio</li>
<li>Applicant’s address state</li>
<li>Loan issue month </li>
    </ul>
    <br>
<b>Bivariate Factors</b>
<ul>
 <li>High loan amount & interest rate for lower income group</li>
<li>Home ownership (mortgaged and rented) and loan purpose (debt consolidation)</li>
<li>Residential state and loan purpose</li>
<li>lowest income and high dti(debt to income ratio)</li>
 </ul>

## Technologies Used
- Numpy
- Pandas
- Seaborn
- Matplotlib

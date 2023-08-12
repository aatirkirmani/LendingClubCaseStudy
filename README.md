# LendingClubCaseStudy
Applying EDA to the loan dataset and developing a basic understanding of Risk Analytics in Banking and Finance.

## Table of Contents
* [Problem Statement](#problem-statement)
* [Dataset](#dataset)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
  
## Problem Statement:
The consumer finance company “Lending Club” specializes in lending various types of loans to its urban customers for a range of purposes. The purpose of the case study is to establish key driver variables that lead to the charge-off (default).
Lending is a very risky business. If loans are accepted for risky applicants, it has a higher probability to result in a financial loss to the company/investors. Therefore, it is essential to find these risky applications and approve loans with stricter conditions (or reject them in some cases) to minimize the losses.
This can also help the company to model risk and create robust risk-mitigating systems/rules.

## Dataset:
The dataset contains records of 39717 unique applications, where each application belongs to one applicant only. The data spans multiple years 2007– 2016 and contains applications from various states of the US.

## Technologies Used:
- Python 3.8.10
- Jupyter Notebooks
- Pandas 1.5.3
- Matplotlib 3.7.0
- Seaborn 0.11.1

## Conclusions:
- Key driver variables for the Loan Charge-Offs:
  - Annual Income (annual income category)
  - Interest Rate (interest rate category)
  - Purpose
  - Grade
  - Sub Grade
  - DTI (Debt to Income Ratio)
  - State
- Low annual income and high-interest rates lead to the high percentage of charge-offs.
- Loans for small business leads to high charge-offs irrespective of the income category.
- Loans for renewable energy lead to high charge-offs unless the income category is not Very High.
- Lower Incomes and Higher Grades lead to high charge-offs.

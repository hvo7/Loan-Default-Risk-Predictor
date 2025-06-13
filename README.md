# Loan Default Risk Dashboard and Analysis

# Problem Statement - Summary
A Bank has experienced too many loans defaulting. How can we solve this issue and thus minimize financial loss?

**Data-Driven Solution** - Create a interactive dashboard and solve hypotheses to help stakeholders determine what factors or applicant profile are likely to default.

## Tools & Stack 
* EDA: **Pandas**, **SQL**
* Data Visualization: **Tableau**
    - We hope to create an interactive dashboard to help specifically non-technical users gain insights into the data.

# Introduction
A bank has experienced an excess amount of approved loans defaulting. This has led to financial losses due to several reasons:
1. Principal loss - Defaulted loans may only pay a portion of what was lent out.
2. Interest Income Loss - Bank misses on future interest payments. 
3. Higher credit risk - Defaulted loans implies poor credit risk assessment, which may dissuade investors and lead to regulatory implications.

The Loan Default Risk Analysis (LDRA) project aims to correctly analyze what factors correlate the most with defaulted loans using data from the LendersClub, the world's largest peer-to-peer lending platform, centralized in San Francisco, California. 

By assessing high-risk loans in advance, we can reduce the amount of loans defaulting and thus minimize financial loss. 

I hope to achieve this by:
1. Creating an interactive dashboard in Tableau for non-technical users by allowing them to filter to what demographic tends have default loans.
2. Explore several hypotheses and overall answer:
    * What does a high risk profile (very likely to default) look like vs. a low risk profile
    * What factors are most associated with default - this may help further feature selection for a risk assessment model

### Data Collection
---
Collect Data From: [TheLendersClub](https://www.kaggle.com/code/faressayah/lending-club-loan-defaulters-prediction)

### Data Cleaning
* Remove duplicates
* Check Null values
* Handle imputation

### Dashboard + Hypothesis Exploration
---
Use SQL to explore the following hypotheses:
* Borrowers with a high debt-to-income (DTI) ratio (above 0.5) are likely to default  
* People who take loans for more leisure activites like vacations are likely to default
* Young borrowers with a low credit history tend to default
* Lower credit score (<600) tend to default

<!----------------- this is for understanding and remembering the markdown languagea syntax--------
## Header 2
**bold**
- bullet 1
- bullet 2
    -[hyperlink name](https://data.cms.gov/search?keywords=healthcare%20claim&offset=10&sort=Relevancy)
>


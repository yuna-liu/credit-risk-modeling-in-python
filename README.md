# credit-risk-modeling-in-python-2021
This repo documents the course contents and my homeworks for the course: [Credit Risk Modeling in Python 2021][link] under Udemy by 365 Careers. This course is a complete data science case study in credit risk: preprocessing, modeling, model validation and maintenance in Python.

[link]: https://www.udemy.com/course/credit-risk-modeling-in-python/

---
## Course methods
The course cover several important data science techniques.

- Weight of evidence

- Information value

- Fine classing

- Coarse classing

- Linear regression

- Logistic regression

- Area Under the Curve

- Receiver Operating Characteristic Curve

- Gini Coefficient

- Kolmogorov-Smirnov

- Assessing Population Stability

- Maintaining a model

---

## dataset that used in this course
1. loan_data_2007_2014.csv 
- The dataset contains all available data for more than 800,000 consumer loans.
- issued from 2007 to 2015 by Lending Club: a large US peer-to-peer lending company. 
- There are several different versions of this dataset. We have used a version available on kaggle.com. You can find it [here][loan_data]: 

[loan_data]: https://www.kaggle.com/wendykan/lending-club-loan-data/version/1

- We divided the data into two periods because we assume that some data are available at the moment when we need to build Expected Loss models, and some data comes from applications after. 

- Later, we investigate whether the applications we have after we built the Probability of Default (PD) model have similar characteristics with the applications we used to build the PD model.

- This dataset is too larger for github, larger than 100mb of the limitation in github. I thereby use gitignore to avoid upload to my github repo.
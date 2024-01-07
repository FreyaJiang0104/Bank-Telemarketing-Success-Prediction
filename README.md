# Supervised Machine Learning Project: Bank Telemarketing Success Prediction

## Background
Within the banking industry, optimizing telemarketing strategy is a key issue. The problem addressed in our project is the prediction of the success of telemarketing calls for selling long-term deposits by a Portuguese retail bank. We aim to develop machine learning models to assist bank marketing campaign managers in selecting the most promising customers to contact during their campaigns. By analyzing a dataset spanning from 2008 to 2010, we will focus on feature engineering and the comparison of five machine learning models to determine the most effective approach for predicting campaign success. The goal is to reduce campaign costs, improve customer targeting, and enhance overall marketing campaign efficiency.

## Data
The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.
| Column    | Description                                       | Dtype | Null | Variable Type |
|-----------|---------------------------------------------------|-------|------|---------------|
| `job`       | type of job                                       | object| Yes  | Categorical   |
| `marital`   | marital status                                    | object| No   | Categorical   |
| `education` | education level                                   | object| No   | Categorical   |
| `default`   | the situation regarding whether a client has credit in default or not | object| Yes  | Categorical   |
| `housing`   | the situation regarding whether a client has a housing loan or not | object| No   | Categorical   |
| `loan`      | the situation regarding whether a client has a personal loan or not | object| No   | Categorical   |
| `contact`   | communication type for contact                    | object| Yes  | Categorical   |
| `day_of_week` | last contact day of the week                     | int64 | No   | Categorical   |
| `month`     | last contact month of year                        | object| No   | Categorical   |
| `poutcome`  | outcome of the previous marketing campaign        | object| Yes  | Categorical   |
| `age`       | the age of each client                            | int64 | No   | Numerical     |
| `balance`   | average yearly balance                            | int64 | No   | Numerical     |
| `duration`  | last contact duration, in seconds                 | int64 | No   | Numerical     |
| `campaign`  | the number of contacts made during this campaign for each client | int64 | No   | Numerical     |
| `pdays`     | the number of days that passed since each client was last contacted in a previous campaign | int64 | No   | Numerical     |
| `previous`  | the number of contacts made before this campaign for each client | int64 | No   | Numerical     |

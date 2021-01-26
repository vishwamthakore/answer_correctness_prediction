# Answer Correctness Prediction
My submission for Riiid Answer Correctness Prediction competition on kaggle.

[*submission_notebook_link*](https://www.kaggle.com/vishwamthakore/loop-features?scriptVersionId=52676531)

## Description
**Features**
1. Content/Question features
- Question Average Accuracy
- Question Frequency (No. of times question is asked)
- Part (Part of test in which question appears)

2. User Features
- User accuracy 
- User total questions
- User total correct questions
- Prior question elasped time
- Prior question had explanation

**Note**- Only data of user before attempting question is used to create train dataset.
---

**Model**- LGBM Classifer

**Evaluation**- AUC Score- 0.754

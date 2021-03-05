# KEY POINTS 
***
---
1. We have used **Lasso** as linear regression model because we want _non negative coefficient_ for the equation. Lasso is model from sklearn library which is used to get non negative coefficient of any linear regression program.

---
2. We have split data into **training and testing data** where training data is used of training the model and testing data is for testing the accuracy of model. We have done this split because if on the same data, if train and test our model that this will not justify accuracy of our model well. So have split the training and testing data. In most of the cases we have used _90% data as training and 10% data as testing_.

---

3. For getting **accuracy of model** we have obtained various dufferent parameter like RMSE, R-square, Adjusted R-square, sum of residuals, F-statistic and p-value.

---

4. We have divided the count of every miss event with the count of total instruation for that particular instance in order to get all the row **value between 0 and 1**.

---

5. At the end we have _obtained CPI from coefficient_ of different miss events and from the CPI of all miss events and base CPI we have build the **CPI stack**.

---
> **Note:-** Detailed explanation of each line of code is attached in the form of _comments_ in code file (_final_regression_code.ipynb_) itself.

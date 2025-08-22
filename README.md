# Titanic - Machine Learning from Disaster

This project is an implementation of the **Titanic: Machine Learning from Disaster** Kaggle challenge using **R**, following [Trevor Stephens’ R tutorial](https://trevorstephens.com/kaggle-titanic-tutorial/getting-started-with-r/).

---

## Project Overview

The Titanic dataset contains information about the passengers on the Titanic, such as age, gender, ticket class, and whether they survived. This project builds a predictive model to determine passenger survival using **R**.  

The workflow and analysis are guided by **Trevor Stephens’ R tutorial**, which demonstrates data cleaning, feature engineering, exploratory data analysis, and predictive modeling techniques.

---

## Objective

- Predict survival of Titanic passengers based on available features.  
- Learn and apply machine learning techniques using R.  
- Practice feature engineering, data visualization, and model evaluation.  

---

## Dataset

The dataset is provided by Kaggle and consists of:

- `train.csv`: Training data including survival outcome.  
- `test.csv`: Test data without survival outcome (used for making predictions for submission).  

---

## Methodology

1. **Data Cleaning**  
   - Handle missing values in `Age`, `Fare`, and `Embarked`.  
   - Convert character variables to factors as required by R models.  

2. **Feature Engineering**  
   - Extract `Title` from passenger names.  
   - Group family sizes into categories.  
   - Combine or transform features to improve model performance.  

3. **Model Building**  
   - Use decision tree-based models such as `randomForest` or `cforest`.  
   - Train models on the training set and predict survival on the test set.  

4. **Evaluation**  
   - Check model accuracy and compare predictions with baseline models.  
   - Prepare submission file in CSV format for Kaggle.

---

## Bugs
 
Create an issue mentioning the bug you have found.

---
### Known bugs

- N/A

---
## Support

Contact [John Wanjema](jonwanjema@gmail.com) for further help/support.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
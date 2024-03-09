



# Problem Statement : 

   ### Task 1 :
**Create a predictive model which will help the insurance marketing team to know which customer will claim the insurance.**.
   ### Task 2 :
**Suggestions to the Insurance market team to make  customers  buy the product.**

## Here are some of the key outcomes of the project:

- The Dataset was large, totally around 6 lakhs samples & before preprocessing 2% of the datasamples were dropped.
- The samples were highly imbalanced hence over sampling, undersampling, SMOTE Technique were applied on the data to balance the classes to the dataset.
- Visualising the distribution of data & their relationships, helped us to get some insights on the relationship between the feature set.
- Feature Selection/Eliminination was carried out and appropriate features were shortlisted.
- Testing multiple algorithms with fine-tuning hyperparamters gave us some understanding on the model performance for various algorithms on this specific dataset.
- The boosting & ensemble algorithms perform the best on the current dataset.

  
## Problems :
- The data is non linear and highly imbalanced which resulted in Over-fitting.
- It was difficult to understand data and pre-process it due to the data and feature names being irrelevant.
- The run time was high during fitting the model.
- Accuracy was good for few models but the problem was presence of several outliers whereas for few models accuracy was poor.
- There are misclassifications and handling them was difficult.
- GridSearchCV and RandomizedCV consumed lot of time and increase in parameters gave memory error. 

# Model Comparision Report :
- We used Logistic Regression, Decision Tree, Random Forest, XGBoost along with OverSampling, UnderSampling also SMOTE and PCA.
- The final model we applied is SEQUENTIAL MODEL which is preferred among all the models as it gave the best accuracy.

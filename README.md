# HR_Attrition_Prediction

This project deals with Attrition in human resources which is nothing but the gradual loss of employees overtime.
High attrition is problematic for companies.
Our aim is to predict a model for human Resource Department to predict the Attrition.

In this dataset ,we have categorical and numerical data and using encoding technique to treat categorical data.

This dataset does not have any missing values and outliers exist in most of the columms and Also columns are rightly skewed as well.

traget variable class is imbalanced,So Used SMOTE () method to balance the imbalanced data.

Builded a model for the algorithms- 
1) Support vector classifier
2) Random Forest Classifier
3) Decision Tree Classifier
4) Ada Boost Classifier

Used Cross_Validation_Score to check the model is under-fit or over-fit

Chosen the best model based on less difference between cross validation score and model accuracy 

Applied Hyper- Parameter tuning for that model which is having less difference and tried to increase the model accuracy.

Finally Saved the model .pkl file.

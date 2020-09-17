## Zimnat-Insurance-Recommendation
Zimnat Insurance Recommendation - Zindi Africa Data Science Competition

------ 

### Overview and Objective

Zimnat is a Insurance company located in Zimbabwe, that has a variety of Insurance Products.
We are given a dataset that consists of a number of demographical variables and for each customer we are also given a set of 21 products along with an indicator if they have that particular product or not (In the training set).

The Task is therefore to use this historic data to predict which products will a customer purchase next out of 21 products.


### Approach and Results

A target variable was not explicitly given, therefore we had to structure the dataset depending on how we wanted to approach the problem.
I approached the problem as a multi-class classification problem. The final model was using the XgBoost Algorithm and I was able to obtain stable and decent score of 0.277 LogLoss.


### Tools/Libraries Used

- Pandas,Numpy,Matplotlib and various Sklearn packages
- SMOTE Technique for oversampling
- Optuna for Hyperparameter Tuning
- XgBoost

### Reference 
See the Zindi link for additional information and to download the data: https://zindi.africa/competitions/zimnat-insurance-recommendation-challenge


# StressTracker
## Data Science Notes 


As a Data Science team, we used Python for developing our project. In order to analyze, clean and understand our data set, we used Numpy, MatPlotlib and Pandas libraries in the first place. After Data cleaning and Data Wrangling we started PEDA (Preliminary Exploratory Data Analysis).
When we completed our statistical analysis, we did our feature selection and get ready for ML model building.
The aim of our notebook and project is to evaluate binary class classification models to predict whether a person is stressed or not-stressed based on Heart Rate Variability (HRV) and other extracted features. Shortly dealing with a type of Supervised Learning Classification problem.
In order to achieve the best result, we build 4 different classification models: 
- Random Forest Classifier
- Support Vector Classifier
- Decision Tree Classifier
- Gradient Boosting Classifier

For each model, we estimate the performance via computing the accuracy, precision-recall, F1 score. We performed the hyperparameter optimization for each algorithm via getting the help of Sklearn's model_selection function  GrindSearchCV()
After our evaluation, we saw that all models gave very good results. However, the Random Forest model showed the best "overall" performance for our data set. We obtained the most balanced trade-off between training cost and accuracy. For this reason, we made a decision that Random Forest is the optimal model to measure the HRV feature set and predict stress. On account of this, our StressTracker App will be based on the Random forest model. 

Please see our ml_models.ipynb notebook for details.  
[https://github.com/TechLabs-Berlin/st21-stress-tracker/blob/main/ml_models.ipynb]

## Salary Prediction Portfolio (Python)

### Goal 
This project aims to developed and deployed a salary prediction application which business’ HR and talent acquisition can use to optimize their compensation strategy, acquire the best talent and improve retention rate in competitive labor market. It answers the question on what is an optimal salary range based on different factors such as job title, years of experience, degree, etc.

### Dataset Information
The dataset are split into 3 different CSV files. 1. Training data 2. Test data 3. Target variable - Salary. There are 1 million observation and 9 features in total.

### Background
This notebook demonstrates the entire data science process of building a predictive model that can hypothetically used by HR to estimate perspective employees' compensation. The processes involving defining the problem, preprocessing data, EDA, developing model, and deploying into production have been divided into main sections. Salary range tends to vary, depending on many factors such as experiences, education, previous job title, etc. This predictive analysis aims to build a scalable and deployable model to predict salary. Here are the breakdown of my project.

1. Data Cleaning and Preprocessing
2. Exploratory Data Analysis to examine the distribution of the target variable and its correlation with categorical and numerical features. 
3. Models built using linear regression, random forest, and gradient boosting. 
4. Models tuning using parameters such as n_estimators, learning rate, tree depth. 
5. Cross validation and select the best model with the lowest Mean Square Error (MSE). 
      - Linear Regression : 380
      - Random Forest: 411
      - Gradient Boosting: 358
  Gradient Boosting turns out to have the lowest MSE on the Cross Validation. Upon predicting on the test dataset, it achieves 358 on the final model.

6. Feature importance data visualization 
7. Deploy and save the final model into production using Pipeline.


### Here is the [Link] (https://github.com/dsjoench/salarypredictionportfolio/blob/master/Salary%20Prediction%20Portfolio%20.ipynb)to my codes
      
### 



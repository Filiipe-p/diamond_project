# Diamonds Price Prediction

# Project Name

  Project status: Completed
  
# Project objective

  The main objective from the project is to predict the price of diamonds from a Dataset with an error not greater than $900, using another data set as model.
  
# Methods

  - Filtering
  - Data cleaning
  - Linear Regression
  - Random Forest Regressor
  - Predicting prices from a model
  
# Technologies 

  - Python
  - Pandas
  - SkLearn
  - Numpy
  - Seaborn
  

# Steps
1.Importing Datasets
  ![image](https://user-images.githubusercontent.com/104516688/204296281-fc9023d2-35ce-40a6-8225-4c4ca380bf21.png)
  
  
2.Transforming cathegoric columns in numeric and filtering Outliers:
 ![image](https://user-images.githubusercontent.com/104516688/204296911-5145c8e2-749f-40eb-9a8e-f95dd562849c.png)

 ![image](https://user-images.githubusercontent.com/104516688/204298452-bfc4f026-c08c-4c9f-808a-2cc448fb796e.png)
 

3.Understanding deeply the data
 ![image](https://user-images.githubusercontent.com/104516688/204299227-dd5c2c3b-009b-4b22-b87b-b1ae1b2488c9.png)


4.Creating the Linear Regression model, and testing the error.
 ![image](https://user-images.githubusercontent.com/104516688/204300834-f599cb33-1dbb-47b1-b93d-20df722fb2e6.png)
 - Not good enough...
 
5.Now Trying the Random Forest model:
 ![image](https://user-images.githubusercontent.com/104516688/204301555-b106247f-906b-4fec-b06f-6b532a45dce4.png)
 - Only $200 error! Time to use this Model on the target Dataset.

6.Cleaning the Target DataSet and saving a new file:
 ![image](https://user-images.githubusercontent.com/104516688/204302974-c60c77b0-bd57-424f-93eb-2a3c0d81ce64.png)

7.Testing the model:
 ![image](https://user-images.githubusercontent.com/104516688/204304314-1f95a448-527a-487f-9865-eb71115ea91c.png)

 ![image](https://user-images.githubusercontent.com/104516688/204304487-84d6d53f-8cf1-4a4b-8639-3d9d1ca20bc1.png)

 Success!!

# Supply-Chain-Shipment-Price-Prediction
## **1. Problem**

For a given supply chain data, let's try to predict the price of product including shipping.

We will use a lots of Classical ML algorithms to make our predictions and at the end decide which suits best for us.

## **2. Data**

The [dataset](https://www.kaggle.com/c/dog-breed-identification/data) we're using is from Kaggle's dog breed identification competition.

## **3. Solution**

After deciding the problem I followed some steps regarding completion of my project

1. Imported all the useful libaries
2. Upload my CSV files 
3. Performed some EDA and got some insights about data
4. Dropped , Cleaned, Encoded and did some useful Feature Engginering 
5. Started preprocessing within a function ‘preprocess_inputs()’
6. Applied Standarization in all respective column’s values
7. Splitted our dataset into Train and Test data
8. Applied Classical ML algorithms such as Linear Regression, DecisionTree , Random forest
9. Choose r^2 score and adjusted r^2 score for filltered out the best method.
10. All the above steps leads that Random Forest Regressor best fit for my Problem

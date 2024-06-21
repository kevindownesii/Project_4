# Project_4

For Project 4, we used a housing data set from Kaggle (https://www.kaggle.com/datasets/sukhmandeepsinghbrar/housing-price-dataset/data) to predict housing price using supervised machine learning (ML) regression model since we had continuous valued variables.  

Our csv file contained 21,613 records of data. 

We utilized the following machine learning tehcniques: 

- Linear Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

 Linear regression is a model for describing the relationship between a numerical response and one or more variables that explains the response.

 Decision tree is a tree-like model of decisions and their possible consequences, including chance event outcomes, resource costs, and utility. 

 Random Forest is a tree-like model that will sample data and build several simpler decision trees. 

 Support Vector Machines (SVM) is a supervised learning model that we can use for classification and regression analysis. SVM separates classes of data points into multidimensional space.

# Results showed the following: 

* Linear Regression using sqaure feet living space came out to an r2 score of 0.49
* Decision Tree came out to a r2 score of 0.61
* Random Forest came out to a r2 score of 0.84
* Support Vector Machine (SVM) came out to a r2 score of -0.05

Utilzing PySpark, we performed SQL qeueries to find the following: 

- What is the average price for a four bedroom house sold per year, rounded to two decimal places.
- What is the average price of a home for each year the home was built that have 3 bedrooms and 3 bathrooms, rounded to two decimal places.
- What is the average price of a home for each year the home was built that have 3 bedrooms, 3 bathrooms, with two floors, and are greater than or equal to 2,000 square feet, rounded to two decimal places.
- What is the average price of a home per "view" rating, rounded to two decimal places, having an average home price greater than or equal to $350,000? Order by descending view rating.

Our analysis showed that Random Forest was the best model to used since its ability to handle non-linear relationships, reduce overfitting through ensemble averaging, and provide insights into feature importance.
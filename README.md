# Predicting Click Through Rate 
Online advertisements are only growing and becoming a huge source of income for companies. Predicting click through rate through specific features and improving these features will increase company revenue durastically.
I hypothesized that the prediction of a click is not due to chance and has to do with the positioning of the advertisement. 
## Data
I used Avazu's data from Kaggle to analyze click through rate prediction. There were three datasets provided, but for the sake of my research, I only utilized the train csv dataset because it already had more than enough entires (over 40 million logs).
 - https://www.kaggle.com/competitions/avazu-ctr-prediction/data
 - https://avazu.com/about/
## Data Cleaning & Exploratory Data Analysis
Before diving into the problem, I cleaned the dataset and performed an EDA to visualize and analyze the data in order to obtain an understanding of what the data consists of. 
The Data Wrangling notebook portrays the shape of the data and the column names. All null and duplicated values were removed and unnecessary rows were dropped.  
The EDA notebook displays all the graphs and visuals made to better understand the features and which features would most likely be correlated or important.  
## Preprocessing & Modeling
The preprocessing Training Data Development notebook shows any necessary changes to the data before the modeling begins. This includes creating dummy features, one-hot encoding features, scaling, and standarization if necessary. 
After the data is preprocessed, the data is ready to be split into testing and training sets in order to begin modeling. 
The Modeling notebook tests three different models that are all appropriate for the data. These include: Logistic Regression, Random Forest, and Gradient Boosting. 
Each model is analyzed and the best representative model is hyper-parametrically tuned with balanced data to obtain the best scores
Among these, the best model was found to be the Random Forest Model with an accuracy score of 0.67 and ROC-AUC Score of 0.72
## Conclusion 
We are able to analyze our results and conclude which features are most indicative of predicting click through rate and how accurate our predictions are. 

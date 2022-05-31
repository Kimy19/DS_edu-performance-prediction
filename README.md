# DataScience_TermProject
 
Classification and clustering with Open University Learning Analytics Dataset

Dataset Link:  
https://www.kaggle.com/datasets/rocki37/open-university-learning-analytics-dataset


## Few function definition for convenient data analysis  
  
1. DecisionTree classifier with K-folds method and GridsearchCV   
Function that implement Gridsearch decisionTree parameters with different K-folds cross validation, returns dataframe of best parameter and best score of each K-fold.
  
![image](https://user-images.githubusercontent.com/87708360/171149566-a75054d1-159f-40f6-a354-f59af2877b82.png)
  
Example function call and result
  
![image](https://user-images.githubusercontent.com/87708360/171149915-f3761acc-0147-40a3-8a7b-5de827d11b4a.png)

    
2.  KNN classifier with Scaling, K-folds method and GridsearchCV 
Function that implement Scaling and Gridsearch KNN parameters with different K-folds cross validation, which returns dataframe of best parameter and best score of each K-fold.  
  
![image](https://user-images.githubusercontent.com/87708360/171150195-4187443f-4ae2-4412-8384-3766e53bd176.png)
  
Example function call and result
![image](https://user-images.githubusercontent.com/87708360/171150247-44cc61d0-1b48-476d-8a7c-ad64423fbbf2.png)

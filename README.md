# Credit Risk Analysis

## Purpose
The goal of this project is to use machiene learning to create a logistic regression to determine if a loan is risky or not risky. The algorithm will determine whether or not the loan is approved or denied. 

## Results 

### Naive Random Oversamping 

-Balanced Accuracy Score: 64.4%
-Precision: 99%
-Recall: 67%

![naive_random_oversampling](https://user-images.githubusercontent.com/75647359/114324847-2c3eac00-9af2-11eb-8e35-33fdd41f0f5f.PNG)

![image](https://user-images.githubusercontent.com/75647359/114325208-7aed4580-9af4-11eb-943d-038af0220ce3.png)

### SMOTE Oversampling 

-Balanced Accuracy Score: 64.8%
-Precision: 99%
-Recall: 64%

![smote_oversampling](https://user-images.githubusercontent.com/75647359/114324908-98211480-9af2-11eb-8062-4302196d7626.PNG)

![image](https://user-images.githubusercontent.com/75647359/114325235-aa9c4d80-9af4-11eb-9bd9-5bf90d6e65ae.png)

### Undersampling 

-Balanced Accuracy Score: 51%
-Precision: 99%
-Recall: 58%

![undersampling](https://user-images.githubusercontent.com/75647359/114324912-9eaf8c00-9af2-11eb-8154-a81c41bd5acb.PNG)

![image](https://user-images.githubusercontent.com/75647359/114325310-fea73200-9af4-11eb-832e-166b43309553.png)

### Combination (Over and Under) Sampling 

-Balanced Accuracy Score: 63.6%
-Precision: 99%
-Recall: 58%

![combination](https://user-images.githubusercontent.com/75647359/114324921-a66f3080-9af2-11eb-80ee-8e333eebf3da.PNG)

![image](https://user-images.githubusercontent.com/75647359/114325327-1f6f8780-9af5-11eb-928c-97b2201e04cc.png)

### Balanced Random Forest Classifier 

-Balanced Accuracy Score: 78.7%
-Precision: 99%
-Recall: 58%

![balanced_random_forest_classifier](https://user-images.githubusercontent.com/75647359/114324978-0cf44e80-9af3-11eb-8af2-955e722f614b.PNG)

![image](https://user-images.githubusercontent.com/75647359/114325155-38c40400-9af4-11eb-8394-7f63faf77c08.png)

### Easy Ensemble Adaboost Classifier 

-Balanced Accuracy Score: 94.3%
-Precision: 99%
-Recall: 94%

![adaboost_classifier](https://user-images.githubusercontent.com/75647359/114324970-05cd4080-9af3-11eb-9416-d1d5a15febcc.PNG)

![image](https://user-images.githubusercontent.com/75647359/114325111-0c0fec80-9af4-11eb-9c23-a4f97b3e8728.png)

## Summary 
Every algorithm shows weak precision when determining if an applicant is high or low risk. While the Ensemble Learning Adaboost method has the highest accuracy score, but when it comes predicting high or low risk, 979 applicants are considered high risk when they are actually low risk. Running this algorithm would miss out on tons of low risk opportunites for banks to invest in. I would not recommend using any of these algorithms. 

# machine-learning-challenge

|   Model  |    Train_Score_Before_CV     |    Test_Score_Before_CV    |    Train_Score_After_CV    |    Test_Score_After_CV    |
|----------|------------------------------|----------------------------|----------------------------|---------------------------|
|SVM       | 0.845508                     | 0.841533                   | 0.886515                   | 0.879290                  |
|LR        | 0.890139                     |0.885011                    |0.892237                    | 0.882723                  |
|RF        | 1.0                          | 0.890160                   | 1.0                        | 0.898169                  |

I tried 3 models that supports classification.

1. Support Vector Machine (SVM) Model
2. Logistic Regression (LR) Model
3. Random Forest model (RF) 

I used the minmax scalar for SVM and RF models but had to use standard scalr model for Logistic regression as a part of preprocessing.

Compared to all the 3 models, random forest had a better variability on the training scores and also had more accuracy on the test scores.

All the models are saved into Models folder.

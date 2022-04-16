# Credit_Risk_Analysis

## Naive Random Oversampling
The accuracy score from this method is fairly low, at 63.6%. This doesn't seem accurate enough for the kind of data model we're trying to make, however, the precision of the model being applied to the data was .99, which is fairly precise.
![resources/Naive%20Random%20Oversampling%20Accuracy.png](https://github.com/KiraLivingston/Credit_Risk_Analysis/raw/main/Resources/Naive%20Random%20Oversampling%20Accuracy.png)
![resources/Naive%20Random%20Oversampling%Precision.png](https://github.com/KiraLivingston/Credit_Risk_Analysis/raw/main/Resources/Naive%20Random%20Oversampling%20Precision.png)

## SMOTE Oversampling
Accuracy was again low, at 63.0%, but precision was high at 99%, overall. This version of sampling also suffers from an in-ability to precisely guess high risk credit, at just 1% precision.
![resources/Smote%20Oversampling%Accuracy.png](https://github.com/KiraLivingston/Credit_Risk_Analysis/raw/main/Resources/Smote%20Oversampling%20Accuracy.png)
![resources/Smote%20Oversampling%Precision.png](https://github.com/KiraLivingston/Credit_Risk_Analysis/raw/main/Resources/Smote%20Oversampling%20Precision.png)

## Undersampling
The precision scores look great for predicting low-risk, at 100%, but not great at predicting low-risk, with just a 1% precision. Accuracy for undersampling is slightly better than the two prior tests, at 64%.
![](https://github.com/KiraLivingston/Credit_Risk_Analysis/raw/main/Resources/Undersampling%20Accuracy.png)
![](https://github.com/KiraLivingston/Credit_Risk_Analysis/raw/main/Resources/Undersampling%20Precision.png)

## Combination Sampling
The precision score are 100% for predicting low-risk and 1% for predicting high-risk, making this another poor choice for identify high-risk credit. Accuracy is also 64%.
![](https://github.com/KiraLivingston/Credit_Risk_Analysis/raw/main/Resources/Combination%20Sampling%20Accuracy.png)
![](https://github.com/KiraLivingston/Credit_Risk_Analysis/raw/main/Resources/Combination%20Sampling%20Precision.png)

## Balanced Random Forest Classifier
The precision scores are beginning to show improvement, at 100% for low-risk and 4% for high risk. The balanced accuracy score is 78.8%, which is much higher than the previous models we've used.
![](https://github.com/KiraLivingston/Credit_Risk_Analysis/raw/main/Resources/Balanced_Random_Forest_Accuracy.png)
![](https://github.com/KiraLivingston/Credit_Risk_Analysis/raw/main/Resources/Balanced_Random_Forest_Precision.png)

## Easy Ensemble AdaBoost Classifier
This model shines the most, with an accuracy at an astounding 93%, and precision at 100% for low-risk, and 8% for high-risk. The high level of accuracy indicates that this is likely the best model to use for this particular dataset. 
![](https://github.com/KiraLivingston/Credit_Risk_Analysis/raw/main/Resources/Easy_Ensemble_Accuracy.png)
![](https://github.com/KiraLivingston/Credit_Risk_Analysis/raw/main/Resources/Easy_Ensemble_Precision.png)
## Conclusion and Recommendations
Looking at all the different models, I can easily recommend that Easy Ensemble AdaBoost Classifier for the best performance, and that we should move forward with that model for further analysis.

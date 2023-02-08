# Credit_Risk_Analysis
Using machine learning to identify good loan candidates for FinTech firms


## Purpose
This endevor was meant to be an overiview of various machine learning alogrithms that use slightly differing approaches to solve the same problem. The problem, in this case, deals with lending by FinTech organizations. Would one algorithm produce more telling results than the others or, perhaps, a clear confidence factor would become known. This would allow for assigning each algorithm a unique degree of value with respecct to how much trust can be given to its quantitative results. 

## Methods
In total, six machine learning algorithms were applied to the 2019 Q1 Loan dataset. Those included:

 1. SMOTE Oversampling 
 2. Naive Random Oversampling
 3. Undersampling
 4. Combination Sampling
 5. Balanced Random Forest Classifier
 6. Easy Ensemble AdaBoost Classifier



## Results
Results for each algorithm are as follows:

Naive Random Oversampling
![Naive](https://user-images.githubusercontent.com/109499859/217662595-802b76e3-1acf-4c19-bf9c-68f39959cf49.png)

SMOTE Oversampling 
![SMOTE](https://user-images.githubusercontent.com/109499859/217662659-f457a17b-1b27-433e-b38b-7dc918e0c6f8.png)

Undersampling
![Undersampling](https://user-images.githubusercontent.com/109499859/217662716-4454f9b2-d167-418f-a4ef-33d15bc916ad.png)

Combination Sampling
![Combo](https://user-images.githubusercontent.com/109499859/217662751-12e9f775-235c-423a-b174-33671f88dab8.png)

Balanced Random Forest Classifier
![Random_Forest](https://user-images.githubusercontent.com/109499859/217662794-8930090a-22c5-435c-bebd-117a02aa6757.png)

Easy Ensemble AdaBoost Classifier
![Easy_Ens](https://user-images.githubusercontent.com/109499859/217662824-6f661f83-735c-49b1-9f55-0206d9d9adda.png)


## Conclusion
When comparing the six algorithms applied to this dataset, there is one clear standout. Considering the classification report results, it is difficult to rule out the strength of the positive values returned by the Easy Ensemble algorithm. The accuracy score came in at over 93%. This would mean that this method should correctly predict 93% of risky loan candidates - a valuable insight in the financial tech sector. 


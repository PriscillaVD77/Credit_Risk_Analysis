# Credit_Risk_Analysis
# Overview 
In this project, we are tasked with analyzing credit score. We use machine learning models to analyze risk of lending based on several credit factors.
## Results
<br>
![Accuracy Score Using Oversampling](oversample_ac.png)
<br>
![Precision and Recall Using Oversampling](oversample_score.png)
<br>
-	Accuracy score: .66  <br>
-	Precision  score: .90  <br>
-	Recall score: .60 <br>
-	f1 score: .75 <br>
<br>
![Accuracy Score Using SMOTE](smote_ac.png)
<br>
![Precision and Recall Using SMOTE](score_score.png)
<br>
-	Accuracy score: .66 <br>
-	Precision  score: .99 <br>
-	Recall score: .69 <br>
-	f1 score: .81 <br>
<br>
![Accuracy Score Using Undersampling](undersample_ac.png)
<br>
![Precision and Recall Using Undersampling](undersample_score.png)
<br>
-	Accuracy score: .57 <br>
-	Precision  score: .99 <br>
-	Recall score: .52 <br>
-	f1 score: .68 <br>
<br>
![Accuracy Score Using SMOTEENN](combine_ac.png)
<br>
![Precision and Recall Using SMOTEENN](combine_score.png)
-	Accuracy score: .56 <br>
-	Precision  score: .99 <br>
-	Recall score: .57 <br>
-	f1 score: .72 <br>
<br>
![Accuracy Score Using BalancedRandomForestClassifier](brfc_ac.png)
<br>
![Precision and Recall Using BalancedRandomForestClassifier](brfc_score.png)
<br>
-	Accuracy score: .79 <br>
-	Precision  score: .99 <br>
-	Recall score: .87 <br>
-	f1 score: .93 <br>
<br>
![Accuracy Score Using EasyEnsembleClassifier](ecc_ac.png)
![Precision and Recall Using EasyEnsembleClassifier](ecc_score.png)
<br>
-	Accuracy score: .93 <br>
-	Precision  score: .99 <br>
-	Recall score: .94 <br>
-	f1 score: .97 <br>
## Summary <br>
The EasyEnsembleClassifier has the highest precision and sensitivity to correct predictions with a high accuracy score of .97. This accuracy is much higher than the other models all between .56 and .66. BalancedRandomForestClassifier model came pretty accurate with a score of .79 with a .97 f1 score showing to have great precision and sensitivity. I would recommend the EasyEnsembleClassifier model since it has the highest accuracy and balanced precision and recall score.

# Classification - Homework 11

### Data Preprocessing

After running the starter code, LabelEncoder() was imported to turn all the columns with strings into integers/floats. 
I found a way to do it with pd.to_numeric but I wasn't sure if this method stores the value as the LabelEncoder does. 

### Resampling 

**Which model had the best balanced accuracy score?**
Naive Random Oversampling has the best accuracy score. 

**Which model had the best recall score?**
Overall, SMOTE oversampling has the best recall score. But specifically for High_risk detection, the Combination SMOTEENN was better with a 0.72 score. 

**Which model had the best geometric mean score?**
Naive Random Oversampling also contains the best geo score. 


### Ensemble 

**Which model had the best balanced accuracy score?**
EAsy Ensemble Classifier with a score of 0.93. 

**Which model had the best recall score?**
Easy Ensemble Classifier. 

**Which model had the best geometric mean score?**
Easy Ensemble Classifier also has the higher geo and is a superior model for this analysis. 

**What are the top three features?**
(0.07269927318199497, 'total_rec_prncp'),
(0.06108290286978353, 'total_pymnt_inv'),
(0.05799241112202666, 'total_rec_int')
**Notebooks:**  
1)	Load data, use relevant columns to compute index of need for the 8 different sectors. Output a new csv file called severity, containing the score for each sector(maximum value is 10).
2)	Processes column related to demographic variables. Transform categorical variables in dummy and aggregate multiple column when needed. Output a csv file demography. These will be our predictors.
3)	Exploratory data analysis. Divide HH in categories from no need to very high need. Try to look at correlation and PCA(principal component analysis). Not find anything immediately evident. Notice that the data are higly imbalanced(most of the HH are in the medium need category), therefore the choice of the classification metric is not trivial. Try different type of ML algorithm.
4)	Try different ML model to deal with the unbalanced data set: Gaussian mixture, Bagging, Random Forest, Bosting, Stacking
5)	Look at SHAP values, i.e look how much each predictor influenced our final predictions
Shapley Value: finding each player’s marginal contribution, averaged over every possible sequence in which the players could have been added to the group

6)	We tried to cluster sector need based on demographic data, however the results were not useful. We then cluster sector needs, finding what kind of needs were usually correlated.

7)During the questionnarie HH members were directly asked what was their first/second/third priority. We compare whether the first sector priority as obtained by our indexes is the same as the one directly reported by HH. 

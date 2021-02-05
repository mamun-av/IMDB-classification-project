# IMDB-classification-project
A classification project that compares different classification models in term of f1_score and classification accuracy. 
The dataset contains 28 variables for 5043 movies, spanning across 100 years in 66 countries. 
Their IMDB score will be divided in 2 groups: higher or equal to 7 and lower than 7.
Our classification models will try to classify the movie into those two groups.

Here is the link of original dataset from dataworld:
https://data.world/data-society/imdb-5000-movie-dataset

Techniques and models used:
- Data cleaning & analysis: Numpy, Pandas
- Data visualization: Plotly, Seaborn
- Data preprocessing OneHotEnconder, SMOTE
- Models: 
	- Linear Classification with LogisticRegression, SGDClassifier
	- SVC
	- DecisionTreeClassifier
	- Ensemble: VotingClassifier, Bagging, RandomForest, Adaboost, XGBoost


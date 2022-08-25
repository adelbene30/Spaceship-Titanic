# Spaceship-Titanic
Included here is my attempt at Kaggle's Spaceship Titanic Competition found at: 
https://www.kaggle.com/competitions/spaceship-titanic

The objective of this competition is to correctly classify passengers that were transported off of the Spaceship Titanic by the anomaly using the features available and any that may be created from them. The training set included 8693 passengers and their records, and the test set included the records of 4277 passengers.

Prior to making a model to make such predictions, the data had to be visualized, cleaned, transformed, scaled, and encoded. Additional features were also created in order to allow both myself and the model to gain a deeper insight into the data. 

* Plotting: Seaborn/Matplotlib
* Scaler: StandardScaler
* Encoder: OneHotEncoder
* Model Used: CatBoostClassifier
* Hyperparameter Tuning: GridSearchCV

After creating a set of predictions using the optimal hyperparameters on the model, a classification accuracy of 80.219%.

<h1 align="center"> Shaloy's Data Science Portfolio</h1>

![--](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## [Project 1: Bike Sharing Demand Prediction](https://github.com/shaloy-lewis/bike_sharing_demand_prediction)
* Implemented a regression model to predict the hourly demand for rental bikes in the city of Seoul based on the weather conditions and other factors.
* The data was available for a duration of one year, and there were a total of 8760 records. 
* Executed regression models (decision tree, random forests, gradient boosting method, XG boost) to obtain RMSE of up to 188.8.
* Optimal hyperparameters were obtained after hyperparameter tuning using grid search cross validation.

![--](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## [Project 2: Cardiovascular Risk Prediction](https://github.com/shaloy-lewis/cardiovascular_risk_prediction)
* Implemented a binary classification model to predict a patient's risk of coronary heart diseases (CHD) over a period of 10 years based on their demography, lifestyle, and medical history.
* The data was gathered from 3390 adults participating in a cardiovascular study in Framingham, Massachusetts
* Only 15% of patients were tested positive for this disease, hence the data was oversampled using SMOTE to handle this imbalance.
* Executed binary classification models (logistic regression, K nearest neighbors, naïve Bayes, SVM, decision tree, random forests, XG Boost) to obtain recall score of up to 77%.

![--](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## [Project 3: Netflix Movies and TV Shows Clustering](https://github.com/shaloy-lewis/Netflix_movies_and_tv_shows_clustering)
* Built clusters using the k means clustering and hierarchical clustering algorithm on 7787 records of Netflix movies and TV shows.
* Generated 20,000 attributes after NLP modelling (tokenization, preprocessing, and TFIDF vectorization). The number of features was reduced using PCA to 4,000, and these 4,000 features were able to account for more than 80% of the variance.
* Optimal number of clusters for the k means (19) and hierarchical (14) clustering algorithm were determined after visualizing the elbow curve and dendrogram respectively.
* Was successful in building clusters with Silhouette score of up to 0.007 for k means clustering algorithm.
* Leveraging the constrained k means clustering method, a basic content-based recommender system was developed, and this recommender system was capable of recommending 10–20 shows to viewers depending on the type of show they had just watched.

![--](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

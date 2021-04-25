# Data Science Portfolio
## Python 3 on Google CoLab

***

# [Movie Recommendation Engine, NLP Content-Based TF-IDF](https://github.com/lmkwytnicholas/nic.github.io/blob/master/contentBasedRecommendation.ipynb)
* **Data**: Kaggle - [TMDB 5000 Movie Dataset](https://www.kaggle.com/tmdb/tmdb-movie-metadata)
* **Objective**: Create a movie recommendation engine using the dataset
* **Methods**: TF-IDF
* **Conclusion**: Movie Recommender takes an input from user, a movie title, and produces 10 movie recommendations from original dataset based on TF-IDF algorithm

***

# [Book Recommendation Engine, NLP Collaborative-Filtering kNN](https://github.com/lmkwytnicholas/nic.github.io/blob/master/collabFilteringNlpBookRecommender.ipynb)
* **Data**: Kaggle - [BookCrossing](https://www.kaggle.com/jirakst/bookcrossing)
* **Objective**: Create a book recommendation engine using the dataset
* **Mehtods**: kNearestNeighbors - Cosine Similarity
* **Conclusion**: Selecting a book (`query_index`) from the dataset produces 5 book recommendations from same dataset based on kNN Cosine Similarity algorithm

***

# [Amazon Fine Foods Reviews, NLP Sentiment Analysis](https://github.com/lmkwytnicholas/nic.github.io/blob/master/amazonSentimentAnalysisBowTfidf.ipynb)
* **Data**: Kaggle - [Amazon Fine Foods Reviews](https://www.kaggle.com/snap/amazon-fine-food-reviews)
* **Objective**: Determine review as positive or negative per sentiment analysis
* **Methods**: Multinomial Naive Bayes of BoW vs. TF-IDF
* **Conclusion**: Of the two alpha values identified between the BoW and TF-IDF vectorizations of text dataset, BoW performed best
	* BoW - Best Alpha - 0.05, AUC - 0.92098 
	* TF-IDF - Best Alpha - 0.05, AUC - 0.90401

***

# [Fake News Classifer, NLP BoW vs. TF-IDF](https://github.com/lmkwytnicholas/nic.github.io/blob/master/fakeNewsBowTfidf.ipynb)
* **Data**: Kaggle - [Fake News](https://www.kaggle.com/c/fake-news/overview)
* **Objective**: Build a system to identify unreliable news articles
* **Methods**: Multinomial Naive Bayes of BoW vs. TF-IDF
* **Conclusion**:
	* BoW - Accuracy Score - 92.05%
	* TF-IDF - Accuracry Score - 89.97%

***

# [Dimension Reduction, PCA](https://github.com/lmkwytnicholas/nic.github.io/blob/master/housingDataPCA.ipynb)
* **Data**: Kaggle - [House Prices - Advanced Regression Techniques
](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)
* **Objective**: Reduce number of features of dataset using Principal Componenet Analysis and then compare performance of Linear Regression between transformed and original data
* **Methods**: PCA
* **Conclusion**: Linear Regression performed better on the original dataset than the transformed data with reduced features using PCA
	* Original - 37 Features - R2: 0.83275
	* PCA - 17 Features - R2: 0.70116

***

# [Determine Optimal K Value with Elbow Method](https://github.com/lmkwytnicholas/nic.github.io/blob/master/autoMpgKmeans.ipynb)
* **Data**: UCI ML Repository - [Auto MPG Data Set](http://archive.ics.uci.edu/ml/datasets/Auto+MPG)
* **Objective**: Determine optimal k-value for k-means clustering using the Elbow Method
* **Models**: K-Means Clustering, Elbow Method
* **Conclusion**: 
	* K-value: 3
	* Silhouette: 0.52586

***

# [Malignant Tumor Classification, Logistic Regression](https://github.com/lmkwytnicholas/nal.github.io/blob/master/tumorClassificationLogReg.ipynb)
* **Data**: Breast Cancer Data from `sklearn`
* **Objective**: Classify whether a tumor is malignant or benign
* **Models**: Logistic Regression
* **Conclusion**: 
	* Accuracy Score: 92.98%

***

# [New Bank Customer Classification, Logistic Regression](https://github.com/lmkwytnicholas/nicholas-lee.github.io/blob/master/New_Bank_Customer_Classification.ipynb)
* **Data**: UCI ML Repository - [Bank Marketing Data Set](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
* **Objective**: Classify whether a customer will become a new customer e.g. - subscribe a term deposit
* **Models**: Logistic Regression
* **Conclusion**: Model fit to dataset proved to be effective for accurately classifying whether a customer will make a term deposit or not
	* Accuracy Score: 90.68%

***

# [Seoul Bike Rental Prediction, Linear Regression](https://github.com/lmkwytnicholas/nicholas-lee.github.io/blob/d0d0b9f4aa8f8963ceffdb97a85e67f65b6e6449/Seoul_Bike_Rental_Prediction.ipynb)
* **Data**: UCI ML Repository - [Seoul Bike Sharing Demand Data Set](https://archive.ics.uci.edu/ml/datasets/Seoul+Bike+Sharing+Demand)
* **Objective**: Determine features that best determine likelihood for renting a bike.
* **Models**: Linear Regression, Lasso & Ridge 
* **Conclusion**: 
	* Lasso (L1) - Training Score: 45.81%, Features: 9
	* Ridge (L2) - Training Score: 45.77%, Features: 9

***




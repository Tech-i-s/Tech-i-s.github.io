# Data Science Portfolio

## Thanks for visiting my portfolio, a collection of my work with datasets and application of machine learning algorithms using Python 3 on Google CoLab.

***

# [Content-Based Movie Recommendation Engine](https://github.com/lmkwytnicholas/nic.github.io/blob/master/contentBasedRecommendation.ipynb)
* **Data**: Kaggle - [TMDB 5000 Movie Dataset](https://www.kaggle.com/tmdb/tmdb-movie-metadata)
* **Objective**: Create a movie recommendation engine using the dataset
* **Models**: TF-IDF
* **Conclusion**: Movie Recommender takes an input from user, a movie title, and produces 10 movie recommendations from original dataset based on TF-IDF algorithm
<img src="images/movieRecEngine.JPG?raw=true"/>


***

# [Collaborative-Filtering Book Recommendation Engine](https://github.com/lmkwytnicholas/nic.github.io/blob/master/collabFilteringNlpBookRecommender.ipynb)
* **Data**: Kaggle - [BookCrossing](https://www.kaggle.com/jirakst/bookcrossing)
* **Objective**: Create a book recommendation engine using the dataset
* **Models**: kNearestNeighbors - Cosine Similarity
* **Conclusion**: Selecting a book (`query_index`) from the dataset produces 5 book recommendations from same dataset based on kNN Cosine Similarity algorithm
<img src="images/collabFilterBook"/>

***

<img src="images/sentimentanalysis?raw=true"/>

# [Sentiment Analysis of Amazon Fine Foods Reviews](https://github.com/lmkwytnicholas/nic.github.io/blob/master/amazonSentimentAnalysisBowTfidf.ipynb)
* **Data**: Kaggle - [Amazon Fine Foods Reviews](https://www.kaggle.com/snap/amazon-fine-food-reviews)
* **Objective**: Determine review as positive or negative per sentiment analysis
* **Models**: Multinomial Naive Bayes for **Bag of Words (BoW)** vs. **Term Frequency - Inverse Document Frequency (TF-IDF)**
* BoW 
<img src="images/BoW"/>
* TF-IDF
<img src="images/TF-IDF"/>
* **Conclusion**:
<img src="images/final"/> 

***

# [Fake News Classifer](https://github.com/lmkwytnicholas/nic.github.io/blob/master/fakeNewsBowTfidf.ipynb)
* **Data**: Kaggle - [Fake News](https://www.kaggle.com/c/fake-news/overview)
* **Objective**: Build a system to identify unreliable news articles
* **Models**: CountVectorizer, BoW vs. TF-IDF, Multinomial Naive Bayes
* **Conclusion**: CountVectorizer, BoW performed better than TF-IDF Vectorizer in identifying fake news with this dataset
<img src="BoWVal"/>
<img src="TfidfVal"/>

***

# [PCA | Linear Regression Performance Comparison](https://github.com/lmkwytnicholas/nic.github.io/blob/master/housingDataPCA.ipynb)
* **Data**: 

***

# [Determine Optimal K Value with Elbow Method](https://github.com/lmkwytnicholas/nic.github.io/blob/master/autoMpgKmeans.ipynb)
* **Data**: UCI ML Repository - [Auto MPG Data Set](http://archive.ics.uci.edu/ml/datasets/Auto+MPG)
* **Objective**: Determine optimal k-value for k-means clustering using the Elbow Method
* **Models**: K-Means Clustering Elbow Method
* **Conclusion**: 
<img src="autoMpg"/>

***

# [Malignant Tumor Classification](https://github.com/lmkwytnicholas/nal.github.io/blob/master/tumorClassificationLogReg.ipynb)
* **Data**: Breast Cancer Data from `sklearn`
* **Objective**: Classify whether a tumor is malignant or benign
* **Models**: Logistic Regression
* **Conclusion**: 
	* Accuracy: 0.92982

<img src="images/tumorConfusionMatrix.jpg?raw=true"/>

***

<img src="images/seoulbikerental.jpg?raw=true"/>

# [Seoul Bike Rental Prediction](https://github.com/lmkwytnicholas/nicholas-lee.github.io/blob/d0d0b9f4aa8f8963ceffdb97a85e67f65b6e6449/Seoul_Bike_Rental_Prediction.ipynb)
* **Data**: UCI ML Repository - [Seoul Bike Sharing Demand Data Set](https://archive.ics.uci.edu/ml/datasets/Seoul+Bike+Sharing+Demand)
* **Objective**: Determine features that best determine likelihood for renting a bike.
* **Models**: Linear Regression, Lasso & Ridge Regression Modeling
* **Conclusion**: 
**Correlation Matrix**
<img src="images/plotCorrMatrix.jpg?raw=true"/>
* **Lasso L1**
* Training Score: **0.45812**
* Number Features: **9**
* **Ridge L2**
* Training Score: **0.45769**
* Number Features: **9**

***

<img src="images/portugesebankcustomer.jpg?raw=true"/>

# [New Bank Customer Classification](https://github.com/lmkwytnicholas/nicholas-lee.github.io/blob/master/New_Bank_Customer_Classification.ipynb)
* **Data**: UCI ML Repository - [Bank Marketing Data Set](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
* **Objective**: Classify whether a customer will become a new customer e.g. - subscribe a term deposit
* **Models**: Logistic Regression
* **Conclusion**: Model fit to dataset proved to be effective for accurately classifying whether a customer will make a term deposit or not
	* Precision: 93%
	* Recall: 97% 

<img src="images/bankCustomerConfusionMatrix.jpg?raw=true"/>

***




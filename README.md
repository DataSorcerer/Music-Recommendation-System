# Music-Recommendation-System

[Check out detailed report and source code](https://github.com/DataSorcerer/Music-Recommendation-System/blob/master/SongsRecommender.ipynb)

Recommender systems are a popular class of information filtering system. The goal of such systems is to predict the preference an user would give to an item/ service and thus "recommend" them with those relevant items. Recommender systems are known to improve user experience on many webportals, especially the ones which involve lots of social interaction or shopping. Here, we explore **content based recommenders** that leverage:   
1. Popularity of items   
2. Matrix Factorization (**Singular Value Decomposition**)

<strong>Dataset:</strong>    
We use the "Taste profile subset" dataset that is auxillary to the popular million songs dataset available at: [The Million Song Dataset](https://labrosa.ee.columbia.edu/millionsong/)
It is a freely-available collection of audio features and metadata for a million contemporary popular music tracks. The purpose of choosing such a large dataset is to build and test <font color="blue">recommender systems at scale</font>. Although the entire dataset is of 280 GB, we deal only with **3 GB** of available sample data which still exhibits characteristics of a large dataset while being moderately computationally intensive to model. 

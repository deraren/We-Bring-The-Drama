# Welcome to our Drama-analysis repository

## About

This is our Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on dramas from [The Movie Database](https://www.kaggle.com/datasets/robertonacu/tmdb-kdramas-2022?select=networks.csv). 

## Notebooks Flow
1.[Data Cleaning - Compilation of necessary data from 5 CSVs.](https://github.com/deraren/We-Bring-The-Drama/blob/main/Data%20Cleaning%20.ipynb)

2.[Initial Discovery - Initial exploratory data analysis with sub-problems.](https://github.com/deraren/We-Bring-The-Drama/blob/main/Initial%20Discovery%20.ipynb)

3.[Main Problem - Exploration of our main problem definition.](https://github.com/deraren/We-Bring-The-Drama/blob/main/Main%20Problem.ipynb)

4.[NLP for Dramas - Use of NLP in classification model and recommender function.](https://github.com/deraren/We-Bring-The-Drama/blob/main/NLP%20for%20Dramas.ipynb)

## Contributors
  -@deraren-Darren Ng

  -@alvis-Alvis Cheng

  -@KapproGlenn Lim

## Problem Definition

- Can we use various publicly accessible statistics to predict how well-perceived a K-Drama will be?

## Exploratory Sub-problems

1.Number of Episodes vs Cast Popularity

2.Episode Runtime vs Popularity

3.Average Rating vs Popularity

4.Cast Popularity vs Popularity

5.Popularity vs Rating Count

6.Popularity vs Number of Seasons


## Models Used
1. Linear Regression
2. Decision Tree Classification
3. Random Forest Classification


## Our Findings and Interpretations

1.It is difficult to predict the goodness of a drama as a continuous variable.

2.Predictors can be used to predict if a show is good (more than or equal to 7.5 average rating).

3.The variables available to the public are better suited for popularity prediction in regression.

4. Multivariate Linear Regression on average rating did not perform well.
 
5.Multivariate Linear Regression on popularity is better but still not too good.

6. More trees/estimators used for Random Forest Classification led to higher classification accuracy.

7. A popular drama does not mean that it is a good drama.
  
8. A drama that has a popular cast does not mean it will be a popular drama.
   
9. A drama that has a popular cast is on fewer networks.
    
10. A high accuracy decision tree classifier may be due to biased predictions.
    
11.A small data range may cause a linear regression model to have low accuracy.



## Learnt Data Science & AI Concepts Through This Journey

1.Resampling imbalanced data.

2.Random Forest classification for binary response.

3.Natural Language Processing (NLP) and textual data cleaning methods.

4.Tokenisation.

5.Lemmatisation with parts of speech tags.

6.Removal of stop words.

7.Bag-of-words.

8.Count and TF-IDF vectorisation methods.

9.Pipeline use with TF-IDF Vectoriser and Random Forest Classifier.

10.Classification reports, includes precision, recall and F1 score.

11.Cosine similarity.



## References

-<https://www.kaggle.com/datasets/robertonacu/tmdb-kdramas-2022?select=networks.csv>

-<https://www.analyticsvidhya.com/blog/2022/01/movie-recommendation-engine-with-nlp/>

-<https://www.geeksforgeeks.org/understanding-tf-idf-term-frequency-inverse-document-frequency/>

-<https://www.geeksforgeeks.org/python-lemmatization-with-nltk/>

-<https://www.machinelearningplus.com/nlp/lemmatization-examples-python/#wordnetlemmatizerwithappropriatepostag>

-<https://towardsdatascience.com/latent-semantic-analysis-sentiment-classification-with-python-5f657346f6a3>


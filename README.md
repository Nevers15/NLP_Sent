# Unsupervised Sentiment Analisys of Smartphone Reviews (NLP)



***STATUS:*** **Incomplete**


## Project Objectives:

Implementation of an unsupervised learning model for sentiment analysis of textual data reviews on smartphones. Separation of comments into two categories, positive comments and negative comments. Analysis of the model's effectiveness.

## Stages: 

1. Text processing. Removal of stop words, smartphone model names, and text lemmatization.
2. Tokenization, creation of a semantic dictionary.
3. Data segmentation into groups using K-means.
4. Multiplication of cluster values by semantic values and addition of the result to the corresponding word.
5. Creation of a TF-IDF dictionary.
6. Replacement of all words in the dataset with TF-IDF values.
7. Multiplication of TF-IDF values and sentiment clusters.
8. Obtaining the result.

## Research Conclusion:

Based on the manual verification of the results, it can be said that the algorithm performs poorly despite being deployed on a large dataset. The main reason for this outcome is the specificity of the Russian language, where positive words can often appear in sentences with a negative tone and vice versa. This is indicated by the identification of key words characterizing a negative tone, including words like "liked", "enjoyed", "excellent." In such cases, it would be more effective to use a supervised learning algorithm. Below is a word cloud of words in negative comments.

<img src="https://i.imgur.com/TovFCLn.png" alt="NLP"/>

## Technical Features of the Project:

The slow performance caused by row-by-row dataframe processing led to many obstacles, reducing the dataframe reduced the quality of the results, so the evaluation of different machine learning algorithms for clustering data caused difficulties, but the fact remains that the result of the work did not improve.

## Project Tools

- Python
- Pandas
- Numpy
- Spacy
- Matplotlib.pyplot
- Sklearn
- Gensim.Word2Vec

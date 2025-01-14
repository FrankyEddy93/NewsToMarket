# Proposal
## Synopsis:

## Objective:

## Data Description:

## Approach: 
 * The set of 25 news for each day needs to be transformed to a format suitable for performing textual analysis and applying predictive model. 
 * We will be using both "BOW" and "n-gram" technique to model the data and perform a comparative performance analysis. 
 
 1: Prepare the corpus 
  * Apply tokenization to separate the English tokens 
  * Stopwords removal and lemmatization 
  * Dictionary creation( bow , n-gram ) 
  * Tf-idf weighting 

 2: Apply Logistic, GNB models on the corpus and up with an accuracy value 

 3: Perform topic modelling 
  * Apply LDA( Latent Dirichlet Allocation ) to come up with a representative topic for each doc 
  * Apply elbow analysis on k-means clustering to come up with an optimal number of topics

 4: Apply sentiment analysis to extract the positive or negative sentiment of the combined docs per day and use this along with lda topics above to see if there are any improvements 
 
## References:

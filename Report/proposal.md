# Proposal
## Motivation:
 *	The basic motivation of this project is to apply machine learning techniques in real life problem to provide insights, and make a good data-oriented decision based on predictions given by the machine learning algorithm
 *	Make use of external data to help predict the market data and its movements
 *	Combine the concepts of machine learning and text analytics to gain better insights both from market data and text data (i.e. News and Forums) 
 *	Expected predcition results are the stock movements in the near future with the input of past and current data

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

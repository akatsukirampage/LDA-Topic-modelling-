# LDA-Topic-modelling-
In this repositories we have classfied the text document using unsupervised LDA.

# About the dataset 
We have given a link of text data of edgars report.

# List of processes performed in this repo.
    - First of all we have to fetch the text data from the given link using python Request and Beautiful soup library
    - After fecting the text data filter the puctuation and number and the word having lenght less than 3 from the data.
    - Now remove the stopwords from the data because they stopwords does not plays any role in topic modeling.
    - Once we done with above steps perform lemmatization on corpus without stopwords and fit resultant corpus to countvectorizer.
    - Intiallize the LDA model with required parameter pass the number of topics you want
    - Define helper function for showing the words of topics 



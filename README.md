# Sentiment-Analysis using NLP
## Data Preprocessing
  - First, we will iterate through each record and using regualr expression, we will get rid of any characters apart from alphabets.
  - Then, we will convert the string to lowercase as, the word "Good" is different from the word "good". This will cause an issue, when we will create vectors of these words, as       two different vectors will be created for the same word which we don't want to.
  - Then we will check for stopwords in the data and get rid of them. Stopwords are commonly used words in a sentence such as "the","an","to" etc. which do not add much value.
  - Then, we will perform lemmatization on each word,i.e. change the different forms of word into a single item called as lemma. A lemma is a base form of a word. For example,    
    run, running and runs are all forms of same lexeme where run is the lemma. Hence, we are converting all occurrences of same lexeme to it's respective lemma.
  - Return a corpus of processed data.
  
***Convert text data to vectors using BOW Model***

## ML MODELS USED
  - SVM
  - RF
  - Multinomial NB

**Best accuracy - 90% on RF after HP tuning**

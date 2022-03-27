# Twitter-Sentiment-Analysis
Learning project for Sentiment Analysis 

Topics 
- Text Preprocessing: 
  - regExp 
  - tokenization
  - lemmatization / stemming
 
- Vectorization: Count & TFIDF & Doc2Vec
- n-grams
### Final Best Model:
  `LogisticRegression(C=1,multi_class='multinomial',solver='saga',penalty='l1')`
  
  TFIDF Vectorizer, `feature = 10000, n-gram = (1,3)`
  

## Data:
Data used for initial model selection:
`data/data_2/Twitter_Data.csv`
- cleaned tweets from kaggle, politics focused, contains non-english words, stemmed

Data used for final model:
`data/sent140/140noemoticon.csv`
- Sentiment 140 Data [source](http://help.sentiment140.com/for-students)

## References 
See Notebooks

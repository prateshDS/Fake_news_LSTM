# Fake_news_classifier_LSTM
Fake news classifier using LSTM.
accuracy score: 0.9133 after performing hyperparameter tunning: Dropout

Steps performed:
1. Since it is NLP based model so we have to perform text preprocessing.
- imputing na values(if required), remove stopwords, remove special characters etc
- perform normalization (Lemmitization or Stemming)
- finally we will have corpus (list of sentences)

2. Perfroming steps to create word embedding layer.
- One hot representation of words(Indexes)  - one_hot
- adding pad_sequence so we can have same number of elements(index) in each sentence
- adding word embedding layer to get specfic dimention(vector) of particular word -  Embedding

3.  Training LSTM model
- prepare data Train and test split - train_test_split
- regularization

4. Model evaluation
- predict - predict 
- perfromance metrix - confusion matrix
- accuracy score - accuracy_score

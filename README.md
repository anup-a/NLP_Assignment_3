# NLP_Assignment_3

Initial task was to preprocess data, and as far as tweets are concerned there are standard procedure to preprocess tweets for sentiment analysis. 
Removal of stopwords
Removal of Punctuation
Removal of Twitter Handles
Removal of Hashtags
Removal of Hyperlinks
Replace emoji with corresponding words
Convert into lowercase 
Next step is the tokenization, so since are just trying out we will begin with the machine learning model. We are using TF-idf vector embedding and pos tagging for the english words.

Second Model is Simple Linear Logistic Regression with degree= 4 , which performs slightly better than SVM, here are the following evaluation metrics for LR:-

Since ML Model are decent, the next step is the neural networks approach. 
Now we have two problems first is the romanised hindi text, which directly neutralises the worth of word level embedding. Hence we try char-level embedding which might perform better with lower number of parameters.
Char-level CNN performs better with LSTM and max-pooling layer. Here are the evaluation metrics for the corresponding Model :- 

References : -
1] LIANG, Xu - Character level CNN with Keras , July 2018 
2] Bedi, Gunjit - A guide to Text Classification(NLP) using SVM and Naive Bayes with Python - 2018

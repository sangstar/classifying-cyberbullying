## Classifying cyberbullying

This is an attempt to get a decent model from [https://www.kaggle.com/andrewmvd/cyberbullying-classification](this) dataset. It's a dataset full of tweets and accompanying labels on the types of cyberbullying it constitutes. I wanted to try making an LSTM neural net and wanted to experiment with GridSearchCV with a KerasClassifier object. I got around 85% accuracy on the test set on first attempt in being able to classify whether a tweet is cyberbullying to some degree or not. I might try multiclass at some point with this data. 
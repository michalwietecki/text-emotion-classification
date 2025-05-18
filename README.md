# text-emotion-classification
In this project we focused on developing a machine learning model that would classify short
texts (for example comments on social media) as various emotions (happiness, sadness,
surprise, neutral etc.). <br>

Our dataset in the beginning only consisted of two columns: the text column and the target class
(emotion) column. To transform it into numerical columnsm we used 3 text
vectorization techniques: 
<li>BOW (Bag of words)</li>
<li>N-gram</li>
<li>Tfidf vectorizer</li>
<br>
For the models, in this project we worked with:
<li>MultinomialNB</li>
<li>SVM</li>
<li>XGBoost</li>
<br>
The final model consisted of 3 models, ensembled using the hard voting technique.<br>
Final accuracy (5-fold cross validation): 0.9061

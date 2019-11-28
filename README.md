# SentimentAnalysis
(BOW, TF-IDF, Word2Vec, BERT) Word Embeddings + (SVM, Naive Bayes, Decision Tree, Random Forest) Base Classifiers + Pre-trained BERT on Tensorflow Hub + 1-D CNN and Bi-Directional LSTM on IMDB Movie Reviews Dataset

# Results for Base Classifiers
 <table style="width:100%">
  <tr>
    <th>Rank</th>
    <th>Word Embedding</th>
    <th>Classifier</th>
    <th>Accuracy</th>
    <th>F1-Score</th>
  </tr>
  <tr>
    <td>1</td>
    <td>BERT Sentence Version (Mean Bert Features per Review)</td>
    <td>SVM</td>
    <td bgcolor="#cedc00">90.35</td>
    <td>0.90</td>
  </tr>
  <tr>
    <td>2</td>
    <td>BERT Sentence Version (Mean Bert Features per Review)</td>
    <td>MLP</td>
    <td>90.32</td>
    <td>0.90</td>
  </tr>
  <tr>
    <td>3</td>
    <td>TFIDF with Stop Words</td>
    <td>SVM</td>
    <td>89.59</td>
    <td>0.90</td>
  </tr>
</table> 


# Results for Deep Neural Networks
<table style="width:100%">
  <tr>
    <th>Rank</th>
    <th>Word Embedding</th>
    <th>Model</th>
    <th>Accuracy</th>
  </tr>
  <tr>
    <td>1</td>
    <td>BERT TensorFlow-HUB</td>
    <td>Bi-Directional LSTM</td>
    <td bgcolor="#cedc00">91.34</td>
  </tr>
  <tr>
    <td>2</td>
    <td>BERT Sentence Version (Mean Bert Features per Review)</td>
    <td>1-D CNN</td>
    <td>85.46</td>
  </tr>
</table>

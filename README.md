 I've used a tweets dataset that contains tweet text with 12 emotions (neutral, worry, happiness, sadness, love, surprise, fun, relief, hate, empty, enthusiasm, boredom and anger) and the goal is to predict the percentage of emotions in a giving text

 To achieve that goal I've used some techniques fist to preprocess the text data :

<li>correct misspelled text</li>
<li>replace English contractions with there meaning (isn't => is not)</li>
<li>remove some punctuations, URLS user mentions and extra spaces</li>
<li>replace emojis with there meaning</li><br>

For the modeling part I've used LSTM's and Roberta base Model:
<li>First a Basic LSTM </li>
<li>LSTM model with glove word embeddings</li>
<li>Roberta Base model </li>
<br>
In the final part, I've made a donut chart that detects the level of emotions is a particular text.

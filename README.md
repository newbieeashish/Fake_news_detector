# Fake News Detector

### The aim of this notebook is to provide an example of how to train an NLP model to detect fake news. Fake news is becoming a bigger and bigger issue in society, with disinformation becoming more widely shared on social media. So, a model to detect and filter out such stories would help to regain a lot of trust in the news we consume. The dataset used is approx. 20,000 examples of both real and fake news stories respectively, consisting of a title, text, subject and date. This notebook will preprocess the text, use GloVe word embeddings to map each word to a numeric vector, then pass the text through an LSTM network. The network will then classify each example as real or fake.

### The dataset for the model can be find at :- https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset


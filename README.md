# Fake News Detection
                                                        PROJECT SUMMARY
**Project Title:**  Fake News Detection

**Background:** Fake news is defined as the intentional dissemination of false or misleading information as news.  Fake news has started to be debated and become an issue in recent years with the rise of social media platforms such as Facebook and Twitter. People may unknowingly propagate fake news, resulting in significant social and political consequences. It is virtually impossible to prevent the spread of fake news. Thus, it is crucial to recognize fake news and differentiate it from real news stories at the early stages.

**Aim:** In this paper, I build a model that categorizes news as fake and real news using deep learning tools using a text-based dataset.

**Dataset:** I use the University of Victoria’s ISOT Fake News Data set. Fake news and real news are separated into two data sets containing approximately 20,000 articles. Furthermore, I use the glove Twitter dataset, which is a pre-trained dataset.

**Technology:**  I use Python to verify and validate the results. Long Short-Term Memory (LSTM) is a recurrent neural network used to analyze variable-length sequential data. Bi-Directional LSTM allows looking at sequences both from front-to-back and back-to-front. This paper presents a fake news detection model based on LSTM and Bidirectional LSTM neural networks. In addition to the neural network, I use a GloVe word embedding for the vector representation of textual words. I use the tokenization technique for feature extraction or vectorization. NLTK is used for removing stopwords and lemmatization. Also, the N-grams technique helps to identify overlapping groups of consecutive words or characters.

**Benefits:** LSTM overcomes short-term memory and vanishing gradient problems that traditional neural networks suffer from. LSTM effectively improves performance by memorizing essential information and detecting patterns. Bidirectional LSTM neural networks allow the networks to have both backward and forward information about the sequence at every time step.

**Drawbacks:** The data set consists mainly of political news. 

**Challenges:** It is challenging to use the dropout technique to address the overfitting problem with LSTMs.

**Results:** The results of the Fake news detection classifier model have been evaluated using accuracy metrics. The model achieved 99.87% accuracy.

                       YouTube videos
1-	Short Version: https://youtu.be/Es05Wf4DX88

2-	Long Version: https://youtu.be/cNMvTUKOHJ8



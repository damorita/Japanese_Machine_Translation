# Japanese_Machine_Translation
For Udacity's Machine Learning Engineer

## Requirements
### Library Requirements
pandas
numoy
Keras
Tensorflow
seaborn

### Technical Requirements
- A GPU Instnace to run the Keras training model.
- This model was made with AWS's p2.xlarge EC2 Instance

## Description
This the capstone project for the Udacity Machine Learning Engineer Nanodegree.


### Project Overview
Deep Learning technology has exponentially expanded the possibilities of machine learning capabilities in recent years. One of the most popular applications of which is in natural language processing and language translation due to the the technology's ability to process the complicated structure that is human language. Thanks to advancements in this field, in 2016, Google announced that it's popular Google Translate services will transition to artificial neural network based algorithms as the foundation of its translation software. Among the various deep neural network architectures, the Recurrent Nueral Network structure is commonly used for NLP tasks due to the temporal & sequential structure of languages. [Google’s Neural Machine Translation System: Bridging the Gap between Human and Machine Translation](https://arxiv.org/pdf/1609.08144.pdf)

In this project, I created a machine learning model that can translate a Japanese sentences to English. Translating between Japanese and English is notoriously difficult due to the vast linguistic differences in the structure, grammar, and vocabulary of the languages. Languages with similar roots or linguistic history are often easier to translate to each other both by humans and machines. However, dissimilar languages often have an added challenge. This project is inspired by this article where an RNN model was built to translate English to French [Language Translation with RNN](https://towardsdatascience.com/language-translation-with-rnns-d84d43b40571). The dataset for this project will utilize the corpus provided by [Yusuke Oda](https://github.com/odashi/small_parallel_enja).


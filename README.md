# NLP_Hands_On_UNIMC
<p align="center">
  <img src="docs\logonlp.png" width="600" />
</p>


Welcome to the NLP Hands-On Sessions Repository, developed for the [Laboratorio di analisi di dati testuali taught at the University of Macerata](https://docenti.unimc.it/marina.paolanti/courses/2023/28788).

This repo amounts to a set of resources to learn foundational concepts of Natural Language Processing (NLP) exploiting Machine Learning, and Deep Learning techniques, applied specifically for NLP applications. Whether you're a novice or a seasoned practitioner, this repository provides a structured series of hands-on sessions designed to elevate you


**What You'll Find:**

* Interactive Jupyter Notebook: Interactive code sessions carefully crafted to cover foundational NLP concepts, from fundamental text preprocessing to advanced deep learning architectures;
* Comprehensive Tutorials: Access comprehensive tutorials that guide you through each step of the NLP pipeline, leveraging popular libraries such as NLTK, spaCy, and PyTorch;
* Supplementary Resources: Find supplementary resources including research papers, blog posts, and external links to deepen your understanding of NLP concepts beyond the sessions.


**Session Topics:**

* Introduction to NLP and Text Preprocessing;
* Text Classification with Machine Learning;
* Sentiment Analysis using Machine/Deep Learning;
* Basic usage of Transformer Architectures;

**How to Use:**

* Clone or download the repository to your local machine;
* Download
* Follow the structured sequence of sessions, starting from the fundamentals and progressing to advanced topics.

## Setting 
### Install Anaconda

* Install [Anaconda](https://www.anaconda.com/download/success);  
* Install VScode from Anaconda Navigator;
* Create another conda environment following the image below.

<p align="center">
  <img src="docs\anaconda_navigator.png" width="600" />
</p>

* Open VScode selecting the novel environment;

### Install all conda packages

* From VScode open a new terminal with ``` Terminal >>> New Terminal ```;  
* In the terminal tipe ``` conda install numpy matplotlib pandas scikit-learn notebook```

## Jupyter Notebooks Sessions

* [NLP 20 newspaper classifier](exercise_1\News_Classifier_Sklearn.ipynb)
* [Movie Reviews Sentiment Analysis](exercise_2\sentiment_scklearn\01-Sentiment-Analysis_sklearn.ipynb)


## Adopted Datasets

* Notebook Topic Classification --> [20 Newsgroups data set](http://qwone.com/~jason/20Newsgroups/)
* Notebook Sentiment Analysis Movies --> [Sentiment Polarity Dataset Version 2.0](https://www.nltk.org/nltk_data/#:~:text=Sentiment%20Polarity%20Dataset%20Version%202.0%20%5B%20download%20%7C%20source%20%5D%0Aid%3A%20movie_reviews%3B%20size%3A%204004848%3B%20author%3A%20Bo%20Pang%20and%20Lillian%20Lee%3B%20copyright%3A%20Copyright%20(C)%202004%20Bo%20Pang%20and%20Lillian%20Lee%3B%20license%3A%20Creative%20Commons%20Attribution%204.0%20International)
* Notebook Sentiment Analysis --> [Sentiment Labelled Sentences](https://archive.ics.uci.edu/dataset/331/sentiment+labelled+sentences)


## For Winzozz users
Open powershell as an administrator and set execution policy with ```Set-ExecutionPolicy Unrestricted```


## Useful References
* https://scikit-learn.org/stable/tutorial/text_analytics/working_with_text_data.html

* https://github.com/Jcharis/Natural-Language-Processing-Tutorials/blob/master/Text%20Classification%20With%20Machine%20Learning,SpaCy,Sklearn(Sentiment%20Analysis)/Text%20Classification%20&%20Sentiment%20Analysis%20with%20SpaCy,Sklearn.ipynb

* https://github.com/justinsowhat/scikit-learn-nlp-tutorial/tree/master

* https://github.com/Jcharis/Natural-Language-Processing-Tutorials/tree/master/NLP_with_SpaCy

* deep learning basics ---> https://colab.research.google.com/github/pytorch/tutorials/blob/gh-pages/_downloads/b5fa995b1432ebc93ea7bfe7ec9daed1/text_sentiment_ngrams_tutorial.ipynb

* deep learning transformer --> https://pytorch.org/tutorials/beginner/transformer_tutorial.html
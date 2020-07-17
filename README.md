# Musk-Internship-Task

This repository contains documentations on POS tagging on any news article and also on classification of news articles.

Dataset has been borrowed from [HardiRathod](https://github.com/HardiRathod/news-topic-classification)


The process of Part of Speech tagging on any news article is as follows:
  * Perform word tokenization on each article of dataframe
  * Use NLTK POS tagger and universally tagging every word.
  * Split Adjective, Article, Conjuction, Noun, Preposition, Pronoun, Verb, Adverb
  * At last, count each part of speech in every article
  
For Topic classification, please study [notebook](https://colab.research.google.com/drive/1cfGmOH5YF1QjamagqSN76rTbmflOycSW?usp=sharing)
  
### Results - 

| Machine Learning Algorithm | Train Accuracy          | Validation Accuracy          | Test Accuracy          |
| -------------------        |:-----------------------:|:-----------------------:|:-----------------------:|
| Logistic Regression  | 0.975                  | 0.960                  | 0.187                  |

## Dependencies

* numpy (http://www.numpy.org/)
* pandas
* os
* zipfile

Install missing dependencies using [pip](https://pip.pypa.io/en/stable/installing/)

## Usage

Once you have your dependencies installed via pip, run the demo script in terminal via

```
jupyter notebook
```
or simply try [colab version](https://colab.research.google.com/drive/1cfGmOH5YF1QjamagqSN76rTbmflOycSW?usp=sharing)

Gaurav Chopra

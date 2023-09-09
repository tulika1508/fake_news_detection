# fake_news_detection
# About
Recently, fake news detection on social media has garnered a lot of attention. A machine learning approach is preferred since the fundamental countermeasure of evaluating websites against a list of labelled fake news sources is rigid. Based on the language of news items, our study attempts to employ Natural Language Processing to quickly identify bogus news.

# Dataset
* "train.csv": A training dataset with the following attributes:
  * id: unique id for news article
  * title: the title of news article
  * author: author of news article
  * text: the text of article(can be incomplete)
  * label: a label that marks the article as potentially unreliable-  1: unreliable , 0: reliable

* test.csv: A testing training dataset with all the same attributes at train.csv without the label.
Link to download training dataset: https://drive.google.com/file/d/1SYxcV2WayqGGTbIJV24k9tSUtBJzlFKr/view?usp=sharing

Testing dataset is uploaded in the repository from where it can be downloaded.

# Accuracy
It gives an accuracy of 0.98 on training dataset and 0.97 on testing dataset.

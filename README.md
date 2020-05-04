## Fake_News_Detector

A type of yellow journalism, fake news encapsulates pieces of news that may be hoaxes and is generally spread through social media and other online media. This is often done to further or impose certain ideas and is often achieved with political agendas. Such news items may contain false and/or exaggerated claims, and may end up being viralized by algorithms, and users may end up in a filter bubble.

In order to tackle the above issue, this is a model that will help us detect fake news deals with fake and real news.

Just a small overview :-

1. Using sklearn I have built a `TfidfVectorizer` in our dataset.

2. Then, I have initialized a `PassiveAggressiveClassifier` and fit the model.

3. In the end, the `accuracy score` and the `confusion matrix` tells how well the model fares.

The data I used for training and testing is a csv file : [news.csv](https://drive.google.com/file/d/1er9NJTLUA3qnRuyhfzuN0XUsoIC4a-_q/view)

# Task 3

Detection of "fake news" - classification of articles with titles. The goal of the task is to develop a classifier that will assign one of four classes based on the content and title of the article (see source for details).

Sources and explanations of the data:
http://www.fakenewschallenge.org/


**Input** : A headline and a body text - either from the same news article or from two different articles.

**Output**: Classify the stance of the body text relative to the claim made in the headline into one of four categories:
* Agrees: The body text agrees with the headline.
* Disagrees: The body text disagrees with the headline.
* Discusses: The body text discuss the same topic as the headline, but does not take a position
* Unrelated: The body text discusses a different topic than the headline


* ```fake_news_detection.ipynb``` contains jupyter notebook with exploratory data analysis, data preprocessing and modeling

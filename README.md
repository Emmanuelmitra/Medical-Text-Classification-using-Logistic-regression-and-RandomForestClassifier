
# Project Title

Medical Text Classification using Logistic regression and RandomForestClassifier


## Packages Used
1.	import pandas as pd 
2.	import numpy as np
3.	import string,
4.	import re
5.	from nltk.tokenize import word_tokenize
6.	from nltk.tokenize import sent_tokenize
7.	from nltk.stem import WordNetLemmatizer 
8.	from sklearn.feature_extraction.text import TfidfVectorizer

## Basic preprocessing 
1.	Splitting the words
2.	Sentence tokenizing
3.	Word tokenizing
4.	Removing special characters 
5.	Removing stop words 
6.	Creating features with the help of TFIDF Vectorizer

## Code Link google colab
https://colab.research.google.com/drive/1nJQ-wkxd1qaz7ZVjywUV4e2yZEF9DzAN?usp=sharing
## Contributing
1.Emmanuel Mitra

2.Panchanand jha

3.Ashpak Shaik 


## Authors

- https://github.com/Emmanuelmitra

## 🔗 Links
https://github.com/Emmanuelmitra

## Lessons Learned

a.	This dataset is imbalanced and very noisy 

b.	A lot of text in transcriptions overlaps across categories

c.	Domain knowledge can be applied to reduce the categories

d.	As it is an imbalanced dataset SMOTE (Synthetic Minority Oversampling Technique) can improve the results

e.	Custom-coded features may improve results on this dataset but may not apply to generic transcription datasets.


## Features

This model classify medical transcriptions to clinical domains given medical specialty.


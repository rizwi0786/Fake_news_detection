# for dataset u can go to 
https://drive.google.com/drive/folders/1FNqB7mnjNUsLpOTagHfq58H5KPRVSZQ8?usp=sharing
# Fake_news_detection
This is a Machine leaarning project for detecting fake news 
if u will entar a news cotent then it will detect eaither this news is fake or not 

# library used
Pandas,
Seaborn,
matplotlib,

# from tqdm import tqdm
for sowing progress bar for large dataset access
# import re
 re stands for regular expression this work on pattern matching and expression matching
# import nltk
 nltk stands for natural language toolkit it is popular toolkit for working on human language
 this is for downloading Punkt resorce from nltk it helps to it is pre trained dataset which help to tokenized text data 
  nltk.download('punkt')

 this stopwords is usefull for removing meaning less words like the a and is are 
nltk.download('stopwords')
# .
from nltk.corpus import stopwords
# . 
from nltk.tokenize import word_tokenize
# . 
from nltk.stem.porter import PorterStemmer
# . 
for visualization of text data 
# . 
from wordcloud import WordCloud
# . 
from sklearn.feature_extraction.text import TfidfVectorizer
# . 
from sklearn.linear_model import LogisticRegression  
# . 
from sklearn.metrics import classification_report 
# . 

in this i have use verious Model to detect the fake news 
# 1st Logistive regression
it is giving result with 98.5% accuracy
# second  Decision Tree Classifier
The accuracy Decision Tree Classifier is around 99% which is almost close to perfect.
#  Gradient Boost Classifier
The accuracy of Gradient Boost Classifier  is around 99% which is almost close to perfect.
# 4th model Random forest classifier
The accuracy of  Random forest classifierr  is around 99% which is almost close to perfect.

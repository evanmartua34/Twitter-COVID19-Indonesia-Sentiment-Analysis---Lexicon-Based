# Twitter-COVID19-Indonesia-Sentiment-Analysis---Lexicon-Based
LEXICON BASED Twitter Bahasa Indonesia Sentiment Analysis
============================================================
This works is an improvement from various sources that is used to explore, generate dataset, and analysis.

Lexicon based sentiment analysis has some flaws such as it only takes the sentiment of each word without really put it on the context and the sentiment score produced is really dependent on the word weighting in the lexicon itself. But for doing analysis from scratch where we dont have the pre labelled data, it really expensive and complicated to do sentiment labelling for not specilized person. Therefore lexicon method come into handy for such scenario in doing sentiment analysis. Put in mind that this methods is minimal usage for learning.

How to use:
1. Data Scrapping and Data set Generation:
	run sentiment_Dataset_Generation.py
	the dataset will be availaible in data/data_extraction
	the keywords that is used here is related to corona pandemic in indonesia
	feel free to modify.
	Dont forget to insert your own twitter credentials

2. Sources modification:
	open modify_sources.ipynb 
	to modify lexicon, stop words and slang words
3. Sentiment and Data Analysis:
	open Analysis.ipynb to do this

Hope that this is usefull.


Regards,

Evan Martua


References:
https://github.com/louisowen6/NLP_bahasa_resources <br>
https://github.com/fajri91/InSet<br>
https://github.com/abhimantramb/elang/blob/master/word2vec/utils/swear-words.txt <br>
https://devtrik.com/python/steeming-bahasa-indonesia-python-sastrawi/ <br>
https://towardsdatascience.com/extracting-twitter-data-pre-processing-and-sentiment-analysis-using-python-3-0-7192bd8b47cf <br>

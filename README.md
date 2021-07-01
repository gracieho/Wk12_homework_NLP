# Wk12_homework_NLP
Submission of Sydney Uni Fintech course Week 12 Homework - Natural Language Processing

This week, we reviewed the news sentiment on Bitcoin and Ethereum, using the News API as a data source.
News paper articles were extracted and the Vadar Sentiment Intensity Analyzer scores were obtained.  It found that Bitcoin sentiment was significantly more positive than Ethereum currently (whether compared from a positive, negative, or compound sentiment score).

A tokenization process was used on the Bitcoin and Ethereum news articles, to remove punctuation, stop words, bring words back to their roots (Lemmatize), and words amended to lower case to allow for better analysis. 
A list of the top 10 bi-grams were extracted.  The most common for Bitcoin was El Salvador (reflecting the recent decision for the country to accept Bitcoin as legal tender), and for Ethereum, a number of different bi-grams were at the top of the list, including general words around cryptocurrency and reference to Bitcoin (reflecting Ethereum's strong follower tendency to Bitcoin's outcomes).
WordClouds were produced to help visualise these key words.

A process to extract Named Entity Recognition (NER) was also completed.  This showed the key NER for Bitcoin was again related to El Salvador, london, miami (likely related to the  recent crypto conference held there).  For Ethereum, the key NER were more general, relating to the network, china, entrepreneurs.


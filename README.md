# CryptoRelevanceScore

Repository of the supervised Relevance Score development for the GDELT CRYPTOCURRENCY CURATED EVENT DATABASE project, dataset acquired between late June/2022 and and early July/2022.

Data for the development of the supervised relevance score was web scrapped from Yahoo! Finance containing 1733 labeled news during 27th of Jun2 2022 and the 8th of July 2022;  
* 546 crypto related news extracted from Yahoo Crypto (https://finance.yahoo.com/topic/crypto) were labeled as 1 and 
* 1187 non-crypto related news extracted from Finance (https://finance.yahoo.com/) and General (https://news.yahoo.com/) were labeled as 0. 

Data was split into 1299 news for training and 434 news for test data. Although a BERT model was initially trained, 

Finally, a Naive Bayes approach was the chosen option achieving the following accuracy, precision, recall, f1-score and AUC: 
97.84 \%, 98.47\%, 94.62\%, 96.50\% and 96.97\% in the train set and 91.70\%, 98.09\%, 75.18\%, 85.12\% and 87.25\% in the test set.

* Dataset name: crypto_relevancescore_from_yahoofinance.csv
* Code for web scrapping Yahoo: 1.1.crypto_and_no_news_for_relevancescore_webscrapping_and_modeldevelopment.ipynb
* Simple EDA of the dataset: 1.2.crypto_and_no_news_for_relevancescore_from_yahoo_EDA.ipynb


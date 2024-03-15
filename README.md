# COVID19-Sentiment-Analysis
The aim of this project is to understand public perception and misinformation using natural language processing tools and machine learning models.

## Description

To analyze the impact of twitter and news information on the Indian populace. We use covid-19 twitter public datasets and regular news scraping to implement this study work. In addition to training supervised learning models on approximately 45,000 tweets, we have implemented these models to ascertain the live public sentiment by collecting real time data from Twitter. We wish to show the simplicity of opinion mining and the large-scale impact of the Omicron pandemic in India. Corroborate opinion mined on Twitter to factual opinion obtained from Google news. Understanding supervised learning methods in the field of natural language processing (NLP). Comparing the results of XGBoost, Logistic Regression, Random Forest classifier and TextBlob algorithms<br>

![image](https://github.com/ParthGodse/COVID19-Sentiment-Analysis/assets/98154485/b0254134-0bf1-433a-8c29-adac48cd9c3b)

## Technology Stack

Languages : Python<br>
Models : XGBoost, Logistic Regression, Random Forest Classifier, TextBlob algorithms<br>
Libraries : nltk, tqdm, sci-kit learn, seaborn, pandas, numpy, matplotlib, skimage, wordcloud<br>
Live Data modules : googlesearch, GoogleNews, newspaper3k<br>
Softwares : Tabelau, Colab

## Data

Used a dataset from Kaggle that has 41,157 rows and 6 columns performing data preprocessing, lemmatization and vectorization before training. We evaluated the results and chose the best model (highest precision and accuracy) to analyze real time news and Twitter data. All twitter data was collected using the Twitter API and keywords were #omicron, #covid19, #coronavirus. These hashtags were used as these words are most trending in India, according to Google trends. The most common hashtag was #coronavirus in red color, closely followed by #covid or #covid19 in yellow and #omicron or the blue line had least appearance, due to recent emergence of the variant. 

Data cleaning involved:
•	Removal of mentions (@person1) in the tweets
•	Removal of hyperlinks to videos and images
•	Replacing next line characters by simple spaces, to reduce word length
•	Removal of stop words and spelling improvement
•	Once data is cleaned, labels are encoded using sklearn label encoder where Positive is 2, Neutral is 1 and Negative is 0.

![image](https://github.com/ParthGodse/COVID19-Sentiment-Analysis/assets/98154485/6f04ca36-21bc-45d3-8af9-31146378b6df)

## Results

![image](https://github.com/ParthGodse/COVID19-Sentiment-Analysis/assets/98154485/d0fa636e-7651-45b6-a118-8fd41a3aade7)

## Visualizations using Tableau

![image](https://github.com/ParthGodse/COVID19-Sentiment-Analysis/assets/98154485/bc3c8927-c770-4c61-9813-ac7961c5c203)

In collaboration with : Aditi Govindu

Hi! I'm a data scientist and this my project repository.

# About me:
I am a formally trained, certified data scientist from INSOFE, Hyderabad with a year of experience as a Software Developer in Standard Chartered GBS, Bengaluru.
Since college, I have been in love with coding. It was there that I found out about data science and AI and I've been actively learning and working in this field ever since.
In my two years (as of writing this) of experience in data science, I have acquired skills and knowledge in:
R, Python, SQL, Java, Machine Learning, Deep Learning, RDBMS and big data tools like Hadoop, Spark, Hive and Impala.

# My Resume:
https://drive.google.com/open?id=1hUGtWl4XZn0_THlC8T0OgBND9zVArIGpif-S8_xQNYs


# Projects:
#### Logistic regression classifier to identify Venture Capital and Non Venture Capital firms from company url (FactSet hackathon)
Built a script to visit company url, scrape data and apply Natural Language Processing techniques and clustering to identify and differentiate between Venture Capital firms and Private companies and extract keywords associated with each to improve query detection via google search.
Steps taken:
* Found out the company type from it's name by identifying keywords such as LLC, LLP, Inc etc. and added it as feature.
* Built a webscraper that visits the company's website and scrapes data from html tags.
* Collected the data into a dictionary corpus of bag of words, applied lemmatization, tokenization, stop word removal and tfidf vectorizer to process the text data.
* Iteratively viewed top ranking words and identified more noise to be added to the list of stop words and vectorized via tfidf.
* Conducted Principal Component Analysis to reduce feature length from ~8100+ to 175 while minimising loss of information.
* Split the data via stratified splitting to maintain class proportions.
* Applied Logistic Regression and conducted hyperparameter tuning to achieve optimal AUC scores on both train and test sets and reduce overfitting. Also made changes to stop words list iteratively to achieve the same.
* Extracted top 20 keywords associated with each class.

#### Predict demand of food products (INSOFE hackathon)
EDA and machine learning to optimize food stock revenue loss by studying product and channel behaviour to predict just the appropriate amount of products to manufacture and detect loss making products.

#### S&P 500 stock data analysis and machine learning
Collected S&P 500 stock data by scraping ticker labels from Wikipedia, analysed stock trends and applied machine learning to automate decision making on whether to buy, sell or hold a given company's stocks.

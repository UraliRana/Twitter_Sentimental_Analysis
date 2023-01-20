# Twitter_Sentimental_Analysis

Description: The dataset contians the 14640 records with 15 features of twitter data.The data is about the passenger who commented the airline with their services via tweets on twitter. In this airline like US Airways, America, Southwest, Delta, Virgin America, United and US Airways. To identify the emotion of the customer regarding airlines in this sentimental analysis was implemented. In this data the sentiment of the tweets is given as airline_sentiment like positive, negative and neutral.The project includes the following steps: data loading, data cleaning and preprocessing, filling missing values, EDA (exploratory data analysis), plotting graphs like pie-charts, histogram, Converting sentiments into binary,Models Implementation, Feature Extraction.

Skills: Data cleaning, Data preprocessing, Data insights, Data visualization, Feature Engineering, Model Building, Feature Extraction,Term frequency-inverse document frequency (TF-IDF).

Technology: Python, Pandas, Numpy, Scipy, Seaborn, Matplotlib, Nltk, nltk.stopwors, corpus, importing models, TF-IDF Vectorizer.

Models: Naive Bayes Model, KNN, Support Vector Machine, Decision Tree Model and Random Forest.

Result: In this project, two features are more important than other and this two features are text and airline_sentiment. Firstly, I have used the stopwords on the comments which eliminate the commomn english words from the comments. Corpus was created which is the collection of the words and I have perform feature extraction method like Count Vectorizer and TF-IDF Vectortizer before the sentiment is encoded using label encoder. After I have tested this all models with both vectoizer and able compare the best model which proves the findings are correct.

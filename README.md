# hackathon
Predicting Stock Market Impact of Tweets using Sentiment Analysis and Machine Learning

In this project, we collected a comprehensive dataset by scraping Elon Musk's tweets from the period of 2022 to 2023, alongside Twitter's stock market data for the same timeframe. We performed data cleaning procedures to ensure the data aligns with our specific use case. The datasets were obtained from Kaggle, a popular platform for open-source datasets.

To gauge the sentiment expressed in Elon Musk's tweets, we employed sentiment analysis techniques. However, we utilized a more sophisticated scoring system that accounts for nuanced sentiment variations. We then correlated the sentiment scores with the observed rise and fall of Twitter's stock prices, enabling us to establish a relationship between sentiment and stock market trends.

To predict the impact of sentiment on Twitter's stock prices, we employed a Linear Regression-based machine learning model. By training the model on the collected data, we were able to forecast the effect on the stock market prices of Twitter based on a given sentiment score.

To enhance the functionality of our solution, we integrated OpenAI's API. This involved utilizing prompt engineering techniques to assign sentiment scores to any text entered by the user. These sentiment scores were then fed into our model, enabling real-time predictions of the change in Twitter's stock prices based on user-generated content.

Through this comprehensive approach that encompassed data scraping, cleaning, sentiment analysis, machine learning, and integration of external APIs, we developed a system capable of predicting stock market behavior by leveraging sentiment analysis of textual data.

https://www.kaggle.com/code/ngyptr/python-nltk-sentiment-analysis/input.
Training takes ~10 minutes with free Google colab compute resources.


# News Headline Sentiment Analysis
### Overview
This data science project aims to provide an automated solution for web scraping today's current news headlines and performing sentiment analysis using a basic LSTM (Long Short-Term Memory) model. The project extracts headlines from various news sources, evaluates the sentiment of each headline, and predicts a continuous sentiment score between -1 and +1. 

### Dependencies
Python 3.x
Beautiful Soup for web scraping
PyTorch for LSTM model
Gensim for Word2Vec embedding
Pandas and Numpy for data manipulation
Requests for web requests
Seaborn and Matplotlib for data visualization

### Data Collection
The project uses web scraping via BeautifulSoup to collect today's news headlines from various news sources. The sources are easily customizable by replacing the naming conventions with different news site urls and headline HTML details. The collected data is stored in a structured format for further processing.

### Sentiment Analysis
Sentiment analysis is performed using a lightweight LSTM regression model. It predicts a sentiment score, ranging from -1 to +1, for a collection of current news headlines.

### Model Training
The project utilizes a basic LSTM model to predict the sentiment of news headlines. The LSTM model is trained on the preprocessed data to learn the relationships between words and sentiments.

Predicted sentiment box plots for three major news providers
![image](https://github.com/ianvet31/newsScraper_Analysis/assets/61299105/8d388c06-3570-4566-b6ea-01dc0d513b8f)

Noisy training curve
![image](https://github.com/ianvet31/newsScraper_Analysis/assets/61299105/9e470711-47ca-43ca-888f-d7d269c98ce4)


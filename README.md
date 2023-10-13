# newsScraper_Analysis

A web scraping project designed to perform sentiment analysis on current news website headlines. The headlines are passed into a simple LSTM regression network trained on a kaggle sentiment analysis dataset https://www.kaggle.com/code/ngyptr/python-nltk-sentiment-analysis/input.
Training takes ~10 minutes with free Google colab compute resources.


### News Headline Sentiment Analysis
# Overview
This data science project aims to provide an automated solution for web scraping today's current news headlines and performing sentiment analysis using a basic LSTM (Long Short-Term Memory) model. The project extracts headlines from various news sources, evaluates the sentiment of each headline, and categorizes them as positive, negative, or neutral.


# Installation
Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/yourusername/news-sentiment-analysis.git
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Usage
Run the data collection script to scrape today's news headlines. Customize the news sources and categories as needed in the config.py file.
bash
Copy code
python scrape_news.py
Run the data preprocessing script to clean and prepare the data for sentiment analysis.
bash
Copy code
python preprocess_data.py
Train the LSTM sentiment analysis model.
bash
Copy code
python train_model.py
After training, you can analyze the sentiment of news headlines using the following script:
bash
Copy code
python analyze_sentiment.py "Your news headline goes here."
Dependencies
Python 3.x
Beautiful Soup for web scraping
TextBlob for sentiment analysis
TensorFlow and Keras for LSTM model
Pandas and Numpy for data manipulation
Requests for web requests
All dependencies are listed in the requirements.txt file.

Data Collection
The project uses web scraping to collect today's news headlines from various news sources. You can customize the sources in the config.py file. The collected data is stored in a structured format for further processing.

Data Preprocessing
Data preprocessing includes cleaning and transforming the collected news headlines. This step involves tasks like text cleaning, tokenization, and feature extraction.

Sentiment Analysis
Sentiment analysis is performed using TextBlob, a natural language processing library. It classifies headlines into three categories: positive, negative, or neutral.

Model Training
The project utilizes a basic LSTM model to predict the sentiment of news headlines. The LSTM model is trained on the preprocessed data to learn the relationships between words and sentiments.

Results
The project provides sentiment analysis results for input news headlines, categorizing them as positive, negative, or neutral. The accuracy and performance of the LSTM model can be evaluated using relevant metrics.

License
This project is open-source and is available under the MIT License. You are free to use and modify the code as needed for your applications.

Feel free to customize this README to suit your specific project requirements and structure. Good luck with your news headline sentiment analysis project!

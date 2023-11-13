# Sentiment Analysis Project

## Introduction

Sentiment analysis involves determining the sentiment expressed in a piece of text, often used to understand the opinions and emotions of individuals. In the context of this project, we aim to contribute to Twitter's efforts to combat the misuse of the platform by creating a robust NLP-based classifier. The goal is to distinguish negative tweets and take measures to block or address such content.

## Data Source

The dataset for this project was obtained from Kaggle and can be found [here](https://www.kaggle.com/datasets/yasserh/twitter-tweets-sentiment-dataset?rvi=1). Each row in the dataset contains the text of a tweet and a corresponding sentiment label. The training set includes a word or phrase from the tweet (selected_text) that encapsulates the provided sentiment.

## About the Dataset
- The dataset consists of 27,481 unique values.

Columns:
- `textID`: Unique ID for each piece of text
- `text`: The text of the tweet
- `sentiment`: The general sentiment of the tweet



## Code Overview

1. **Understanding the Dataset & Cleanup:**
   - Loaded the dataset from 'Tweets.csv'.
   - Explored and cleaned the dataset, handling missing values and preprocessing the text.

2. **Building Classification Models:**
   - Developed classification models to predict Twitter sentiments.
   - Implemented two classifiers: Multinomial Naive Bayes and Logistic Regression.

3. **Comparison of Evaluation Metrics:**
   - Compared the evaluation metrics of various classification algorithms.
   - Utilized metrics such as accuracy, confusion matrix, and classification report.

## Key Dependencies

- numpy==1.23.3
- pandas==1.4.3
- matplotlib==3.5.2
- seaborn==0.12.0
- wordcloud==1.8.2.2
- scikit-learn==1.1.1
- nltk==3.7

## Usage

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/Sentiment-Analysis-Project.git

2. **Install Dependencies:**


   ```bash
   pip install -r requirements.txt

3. **Run the Jupyter Notebook:**

*Ensure that you have Jupyter Notebook installed in your Python environment. If not, you can install it using:*

```bash 
pip install jupyter

```


Start Jupyter Notebook by running the following command in the project directory:

   ```bash
   jupyter notebook

```

- Your default web browser will open, and you can navigate to SentimentAnalysis.ipynb in the Jupyter Notebook interface.

OR 

- Open the project folder in your preferred IDE (e.g., VSCode, PyCharm) and run the script.

*Feel free to customize the code according to your specific needs or further insights.*

made by payal soni❤️

# Sentiment Analyzer

## Description
The Sentiment Analyzer project is a tool designed to analyze the sentiment of text data. It evaluates the emotional tone behind a series of words to determine whether the expressed sentiment is positive, negative, or neutral. This project can be utilized in various applications, including social media monitoring, customer feedback analysis, and market research.

## Introduction
Sentiment analysis, also known as opinion mining, is a natural language processing technique used to understand the sentiment conveyed in textual data. This README serves as a guide for utilizing the Sentiment Analyzer tool effectively.

## Features
- Analyze sentiment: Determine whether text data expresses positive, negative, or neutral sentiment.

## Installation
To install the Sentiment Analyzer, follow these steps:
1. Clone the repository from GitHub: `git clone https://github.com/arifzanko/sentiment-analyzer.git`
2. Navigate to the project directory: `cd sentiment-analyzer`
3. Create a `.env` file in the project directory.
4. Inside the `.env` file, add the following lines:
You can obtain your authorization token from huggingface website
```python
API_URL=https://api-inference.huggingface.co/models/cardiffnlp/twitter-roberta-base-sentiment-latest
AUTHORIZATION_TOKEN=YOUR_AUTHORIZATION_TOKEN_HERE
```
5. Install dependencies: `pip install -r requirements.txt`
6. Run the Fast API: `uvicorn new_api:app --reload`
7. Open another CLI and run the Streamlit application: `streamlit run app.py`

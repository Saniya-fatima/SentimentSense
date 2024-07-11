
# Sentiment Sense

Sentiment Sense is a project that combines the power of VADER sentiment analysis with RoBERTa-based sentiment classification to analyze the sentiment of textual data.

![Screenshot 2024-07-11 130828](https://github.com/Saniya-fatima/SentimentSense/assets/122198174/3514311e-a6fb-4931-88b2-58f2a936d599)
![Screenshot 2024-07-11 130813](https://github.com/Saniya-fatima/SentimentSense/assets/122198174/bc4c6e34-b5d5-4fac-a5d7-9ff36c92e263)
![Screenshot 2024-07-11 130745](https://github.com/Saniya-fatima/SentimentSense/assets/122198174/668bf857-c822-4957-b2bf-dd34104d9807)

## Overview

This project uses two main approaches to analyze sentiment:

1. **VADER Sentiment Analysis**: A rule-based sentiment analysis tool that is specifically attuned to sentiments expressed in social media.
2. **RoBERTa Model**: Fine-tuned RoBERTa model for sequence classification, specifically trained for sentiment analysis tasks.

## Features

- **VADER Sentiment Analysis**: Provides quick sentiment polarity scores (positive, negative, neutral, compound) for text data.
- **RoBERTa Model**: Offers more nuanced sentiment analysis with a focus on social media language patterns.
- **Integration**: Combines results from both VADER and RoBERTa to provide comprehensive sentiment analysis results.

## Requirements

- Python 3.6+
- TensorFlow
- Transformers library from Hugging Face
- NLTK for VADER sentiment analysis
- pandas for data handling
- tqdm for progress bars

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/sentiment-sense.git
   cd sentiment-sense
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Download NLTK data for VADER sentiment analysis:

   ```python
   import nltk
   nltk.download('vader_lexicon')
   ```

## Usage

1. **Data Preparation**:
   - Prepare your data in a CSV format with columns for `Id` and `Text`.

2. **Run Sentiment Analysis**:
   - Modify and run the script in Jupyter Notebook or any Python environment:

     ```python
     python sentiment_analysis.py
     ```

   - Ensure to replace the example dataframe (`df`) with your actual data.

3. **Output**:
   - The script will output sentiment analysis results combining VADER and RoBERTa scores for each text entry.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your improvements or bug fixes.



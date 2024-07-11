
# Sentiment Sense

Sentiment Sense is a project that combines the power of VADER sentiment analysis with RoBERTa-based sentiment classification to analyze the sentiment of textual data.

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



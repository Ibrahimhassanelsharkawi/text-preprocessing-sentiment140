# Text Preprocessing - Sentiment140

This project applies text preprocessing and normalization steps on the Sentiment140 Twitter dataset.

## Dataset
- **Name:** Sentiment140 (1.6 million tweets)
- **Source:** [Sentiment140 on Kaggle](https://www.kaggle.com/datasets/kazanova/sentiment140)
- **Sample used:** a random balanced sample of 20,000 tweets (10,000 negative + 10,000 positive), saved in `Data/preprocessed.csv`.

> The original dataset is not included in this repo because of its size (over 100MB). Download it from the link above.

## Preprocessing Steps
1. Segmentation (sentence splitting)
2. Twitter-specific cleaning (URLs, mentions, hashtags)
3. Tokenization
4. Removing punctuation and numbers
5. Removing stop words
6. Lemmatization

## Files
- `Preprocessing.ipynb`: the full code
- `Data/preprocessed.csv`: the preprocessed sample

## Requirements
`pandas`, `nltk`

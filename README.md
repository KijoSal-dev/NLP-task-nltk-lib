# NLP-task-nltk-lib

# NLP Sentiment Analysis with NLTK

This project demonstrates how to perform sentiment analysis on text using Python’s NLTK library and the VADER sentiment analyzer.

## Setup

1. **Create and activate a virtual environment (optional but recommended):**
   ```
   python -m venv .venv
   .venv\Scripts\activate
   ```

2. **Install dependencies:**
   ```
   pip install nltk
   ```

## Usage

1. Run the script:
   ```
   python sentiment_example.py
   ```

2. The script will:
   - Download the VADER lexicon (if not already present)
   - Analyze the sentiment of a sample sentence
   - Print the sentiment scores

## Example Output

```
Sentiment Scores: {'neg': 0.0, 'neu': 0.314, 'pos': 0.686, 'compound': 0.8648}
```

## Notes

- Avoid naming your script `nltk.py` to prevent import conflicts.
- You can change the `text` variable in `sentiment_example.py` to analyze different sentences.

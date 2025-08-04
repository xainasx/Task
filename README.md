# News Clusterizer

## Overview

**News Clusterizer** is a Python-based tool that fetches news headlines from various RSS feeds, preprocesses and cleans the data using NLP techniques, and automatically clusters the headlines into key categories using machine learning. The tool also allows users to predict the category of any new search string using the trained model.

## Features

- Fetches news headlines from multiple RSS news sources
- Cleans and preprocesses text data (stopword removal, lemmatization, tokenization)
- Uses TF-IDF vectorization and KMeans clustering to group news headlines
- Interactive prediction: input your own headline and get its predicted category (e.g., Sports, Climate, Technology)
- Easily extensible for new categories or data sources

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/xainasx/Task.git
   cd Task
   ```
2. Install Python dependencies:
   ```bash
   pip install feedparser nltk scikit-learn pandas numpy
   ```

3. Download NLTK data:
   ```python
   import nltk
   nltk.download('stopwords')
   nltk.download('wordnet')
   nltk.download('punkt')
   ```

## Usage

Open and run the `News Clusterizer.ipynb` notebook. The notebook will:

1. Fetch and display the number of news headlines collected.
2. Preprocess and clean the titles.
3. Cluster the headlines into categories.
4. Allow you to input new headlines and predict their categories.

## Example

```
Do you want to search? 'y' or 'n': y
Write here: SpaceX launches new satellite
Your search string prediction: Technology
```

## Sources

- BBC Sport, ESPN, CNN Sport, Wired, BBC Technology, Gizmodo, Inhabitat, and more.

## License

[MIT License](LICENSE)

---

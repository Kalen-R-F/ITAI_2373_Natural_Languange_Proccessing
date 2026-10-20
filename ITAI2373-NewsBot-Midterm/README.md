# NewsBot Intelligence System

## Project Overview
NewsBot is an NLP-based news intelligence system that processes news articles, predicts their categories, analyzes sentiment, extracts named entities, and identifies linguistic patterns.

## Business Use Case
The system is designed to help journalists, media monitoring teams, researchers, and business analysts organize and analyze large collections of news articles more efficiently.

## Dataset
- **Source:** [Kaggle BBC News Classification](https://www.kaggle.com/competitions/learn-ai-bbc/data)
- **Categories:** Business, Entertainment, Politics, Sport, Tech
- **Input:** Full-text English news articles with category labels

## Technologies
- Python
- Google Colab
- pandas and NumPy
- NLTK
- spaCy
- scikit-learn
- Matplotlib and Seaborn

## NLP Techniques
1. Text cleaning, tokenization, stop-word removal, and lemmatization
2. TF-IDF feature extraction and category-specific keyword analysis
3. Part-of-speech tagging and grammatical pattern analysis
4. Dependency parsing and approximate subject-action-object extraction
5. Sentiment analysis and lexicon-based emotion analysis
6. Multi-class text classification and model comparison
7. Named entity recognition and entity co-occurrence analysis

## How to Run
1. Open the notebook in Google Colab.
2. Accept the Kaggle competition rules and configure the Kaggle API.
3. Run the notebook cells in order.
4. Review the model metrics, charts, and extracted entities.
5. Test the NewsBot with a new article.

## Limitations
The sentiment and emotion analyses are lexicon-based. Dependency-based relationships are approximate, and entity co-occurrence does not establish a confirmed relationship. Model performance depends on the dataset and the selected training configuration.


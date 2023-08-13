# Amazon-Customer-Sentiment-Analysis-Using-Transformers

## Data Preprocessing and Sentiment Analysis

### Used Libraries for Data Preprocessing, Sentiment Analysis, and Machine Learning:
- Utilized NLTK (Natural Language Toolkit) and Sklearn (Scikit-learn) libraries.
- Employed these libraries for text preprocessing, sentiment analysis, and machine learning model development.

### Performed Text Preprocessing and Sentiment Analysis:
- Preprocessed text data by converting to lowercase, tokenizing, stemming, and removing stop words.
- Utilized the VADER sentiment analysis tool to calculate sentiment scores for each review.
- Defined sentiment labels (positive, negative, neutral) based on VADER scores.
- Limited the dataset to the first 100,000 rows for analysis.

### Trained Support Vector Machine (SVM) Classifier for Sentiment Prediction:
- Split the dataset into training and testing sets for model evaluation.
- Applied TF-IDF vectorization for feature extraction.
- Trained an SVM classifier using the TF-IDF features.
- Predicted sentiment labels using the trained SVM model.
- Achieved accuracy measurement for the SVM classifier on the testing set.

### Libraries Used:
- NLTK (Natural Language Toolkit)
- Pandas
- Sklearn (Scikit-learn)

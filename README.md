# Restaurant Reviews Sentiment Analysis

## Overview

This project focuses on analyzing restaurant reviews to determine customer sentiments—classifying them as positive or negative. By leveraging Natural Language Processing (NLP) techniques, the system aims to assist restaurant owners in understanding customer feedback and improving service quality.

## Features

- **Data Collection**: Utilizes a dataset of restaurant reviews.
- **Data Preprocessing**: Cleans and prepares text data for analysis.
- **Sentiment Classification**: Applies machine learning models to categorize reviews.
- **Performance Evaluation**: Assesses model accuracy and effectiveness.

## Methodology

1. **Data Preprocessing**
   - **Text Cleaning**: Removes punctuation, numbers, and special characters.
   - **Tokenization**: Splits text into individual words.
   - **Stop Words Removal**: Eliminates common words that do not contribute to sentiment.
   - **Stemming/Lemmatization**: Reduces words to their root forms.

2. **Feature Extraction**
   - **Bag of Words (BoW)**: Represents text data as numerical features.
   - **TF-IDF**: Weighs the importance of words in the corpus.

3. **Modeling**
   - **Training**: Uses algorithms like Naive Bayes, Logistic Regression, or Support Vector Machines.
   - **Validation**: Evaluates models using metrics such as accuracy, precision, recall, and F1-score.

## Dataset

- **Source**: The dataset is included in the repository as `retauraunt NLP.tsv`.

## Installation

### Prerequisites

- Python 3.x
- Libraries: pandas, numpy, scikit-learn, nltk

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/mohamedsalama677/Restaurant_Reviews.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Restaurant_Reviews
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the analysis script:
   ```bash
   python retauraunt\ NLP.py
   ```

## Applications

- **Customer Feedback Analysis**: Helps businesses understand customer satisfaction.
- **Service Improvement**: Identifies areas needing enhancement based on negative reviews.
- **Market Research**: Analyzes trends in customer opinions.

## Limitations & Future Work

- **Challenges**: Handling sarcasm, context, and ambiguous sentiments in text.
- **Future Enhancements**: Incorporating deep learning models and expanding the dataset for better accuracy.

## Contributors

- Mohamed Salama ([GitHub](https://github.com/mohamedsalama677))

For detailed analysis and code implementation, refer to the [`retauraunt NLP.py`](https://github.com/mohamedsalama677/Restaurant_Reviews/blob/main/retauraunt%20NLP.py) script. 

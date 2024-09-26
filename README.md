# Sentiment-Analysis-of-IMDB-Movie-Reviews

## Overview
This project implements **Sentiment Analysis** on movie reviews from the **IMDB dataset** using **Natural Language Processing (NLP)** techniques. The project is designed to classify reviews as either positive or negative by processing textual data, extracting features, and applying machine learning models.

## Features
- **Data Preprocessing**: Includes data cleaning, tokenization, and removal of stopwords.
- **Feature Extraction**: Uses methods like TF-IDF (Term Frequency-Inverse Document Frequency) to convert text data into numerical representations.
- **Sentiment Classification**: Builds machine learning models (e.g., Logistic Regression, SVM) to classify the sentiment of the reviews.
- **Evaluation Metrics**: Measures the performance of models using accuracy, precision, recall, and F1-score.

## Technologies Used
- **Python**: For developing the core logic and processing data.
- **Pandas & NumPy**: For data manipulation and analysis.
- **Scikit-learn**: To implement machine learning models and evaluate their performance.
- **NLTK/Spacy**: For text processing and NLP techniques.
- **Jupyter Notebook**: For code implementation and result visualization.

## Setup and Installation

### Prerequisites
- **Python 3.x** installed on your system.
- **Jupyter Notebook** to run the project.
- Libraries such as `pandas`, `numpy`, `scikit-learn`, `nltk`, and `matplotlib`.

### Installation Steps
1. Clone the repository:
   ```
   git clone https://github.com/your-username/imdb-sentiment-analysis.git
   ```

2. Navigate to the project directory:
   ```
   cd imdb-sentiment-analysis
   ```

3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook to explore the project:
   ```
   jupyter notebook AIT_526_PROJECT_PROPOSAL_GROUP_8.ipynb
   ```

## Data Source
The project uses the IMDB Movie Review Dataset containing 50,000 reviews. The dataset includes both positive and negative reviews labeled for sentiment classification.

## Usage
Exploration and Visualization: The notebook includes visualizations of word distributions and common phrases in positive and negative reviews.
Model Training: The notebook trains multiple models, including Logistic Regression and Support Vector Machines, for binary classification.
Evaluation: The performance of the models is evaluated using metrics such as accuracy, precision, recall, and F1-score.
   

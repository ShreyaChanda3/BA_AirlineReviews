# Sentiment Analysis on British Airways Reviews

## Introduction
 The primary aim is to deduce the sentiments expressed by the passengers and link these sentiments to overall customer satisfaction and service improvement strategies.

## Project Objectives
The objectives of this project include:
- Analyzing sentiments from customer reviews of British Airways.
- Understanding how sentiments relate to overall customer satisfaction.
- Predicting sentiments based on the textual content of reviews.

## Dataset
The dataset used for this analysis was sourced from Kaggle and consists of customer feedback collected from AirlineQuality. The data was preprocessed to ensure quality and relevancy:
- **Cleaning Steps**: Removal of extraneous columns, handling missing values, text data preprocessing (including lowercasing, stemming, and stopword removal).
- **Features Used**: Cleaned review texts with encoded sentiment labels (positive/negative).

## Tools and Technologies
The analysis was performed using Python within a Jupyter Notebook environment. Key libraries utilized include:
- `numpy` and `pandas` for data manipulation,
- `matplotlib` and `seaborn` for data visualization,
- `scikit-learn` and `xgboost` for machine learning modeling.

## Analysis and Results
### Exploratory Data Analysis
As I examined sentiment polarity and subjectivity, revealing predominantly positive sentiments among the reviews, with a detailed look into customer opinions and experiences.

### Predictive Modeling
- **Models Deployed**: XGBoost Classifier, Random Forest Classifier, and Decision Tree Classifier.
- **Feature Representation**: TF-IDF vectorization.
- **Evaluation**: Models were evaluated based on accuracy, with detailed confusion matrices to illustrate performance.

## Key Findings
The analysis identified key areas where British Airways excels and areas needing improvement. Positive reviews frequently highlighted the professionalism and friendliness of the staff, while negative feedback often pointed to discomfort and service issues.

## Limitations and Future Work
The current study is limited to textual analysis of customer reviews, which may contain inherent biases and does not encompass the full spectrum of customer experiences. Future work could integrate additional data sources and employ advanced NLP techniques to broaden the scope and depth of the analysis.

## Installation and Usage
To run this project, clone the repository and ensure you have the required dependencies installed:
```bash
git clone https://github.com/yourgithubusername/sentiment-analysis-british-airways.git
cd sentiment-analysis-british-airways
pip install -r requirements.txt
jupyter notebook SentimentalAnalysisOnflights.ipynb

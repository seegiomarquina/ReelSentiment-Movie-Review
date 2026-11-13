# ReelSentiment – AI Movie Review Intelligence

## Project Overview
ReelSentiment is a Natural Language Processing (NLP) project that classifies movie reviews as positive or negative using machine learning.

It uses the IMDb movie review dataset, TF-IDF text vectorization, and Logistic Regression to identify sentiment patterns in written reviews.

## Problem Statement
Movie platforms receive large volumes of user reviews. Manually understanding the overall opinion of viewers is time-consuming. This project demonstrates how NLP and machine learning can automatically classify review sentiment.

## Technologies Used
- Python
- Pandas and NumPy
- Scikit-learn
- NLTK concepts / text preprocessing
- TF-IDF
- Logistic Regression
- Matplotlib and Seaborn
- Google Colab

## Dataset
Stanford IMDb Large Movie Review Dataset  
https://nlp.stanford.edu/~amaas/data/sentiment/

The dataset contains 50,000 labeled movie reviews, divided into training and testing sets.

## Project Workflow
1. Dataset loading and inspection
2. Exploratory Data Analysis
3. Text preprocessing
4. TF-IDF feature extraction
5. Baseline model development
6. Logistic Regression training
7. Model evaluation
8. Confusion matrix analysis
9. Custom review sentiment prediction

## Model Evaluation
The project evaluates performance using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Actual evaluation results are available in the `outputs` folder.

## Repository Structure
```text
ReelSentiment-Movie-Review-NLP/
│
├── ReelSentiment_Movie_Review_Analysis.ipynb
├── tfidf_vectorizer.pkl
├── reelsentiment_model.pkl
├── requirements.txt
├── .gitignore
├── README.md
│
└── outputs/
    ├── classification_report.csv
    ├── confusion_matrix.csv
    ├── word_importance.csv
    └── model_comparison.csv
```

## How to Run
1. Clone this repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Open the notebook in Google Colab or Jupyter Notebook.
4. Run the notebook cells in sequence.

The notebook downloads the dataset when executed.

## Future Improvements
- Implement transformer-based sentiment classification.
- Add a movie review web application.
- Support multilingual reviews.
- Deploy the model through an API.
- Monitor performance on new review data.

## Author
Aditya Dhage

Data Science Student | Machine Learning | NLP | Python

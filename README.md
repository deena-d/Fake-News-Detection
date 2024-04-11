# Fake News Detector

This is a simple fake news detector app built using Streamlit. It uses a logistic regression model trained on a dataset of news articles to classify whether a given news article is fake or real.

## Usage

1. **Input**: Enter a news article in the text input box.
2. **Prediction**: Click the "Predict" button to see whether the entered news article is fake or real.

## Setup

### Requirements

Install the required Python packages using the following command:
streamlit==1.0.0
numpy==1.21.5
pandas==1.3.5
scikit-learn==0.24.2
nltk==3.6.5

## How to Run
To run the app, execute the following command:

streamlit run app.py


## Dataset
The dataset used for training the model is available in train.csv. It contains articles labeled as either fake or real.

## Model Training
The logistic regression model is trained using the TF-IDF vectorized representation of the news articles. The model achieves good accuracy on the provided dataset.

##Credits
This project is created by DEENA D.

## Demo video



https://github.com/deena-d/Fake-News-Detection/assets/107647091/5618229a-8cdd-40df-8b27-a3e99e1bff2a


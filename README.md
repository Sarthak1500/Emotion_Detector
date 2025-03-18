# Emotion Detection

## Overview
This project is an Emotion Detection application that analyzes text input and predicts the corresponding emotion (Happy, Sad, or Angry). It is built using Python and Streamlit for an interactive web interface.

## Features
- Takes user-input text and predicts emotions.
- Uses a trained Logistic Regression model for classification.
- Implements TF-IDF vectorization for text preprocessing.
- Supports text cleaning and stopword removal.

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd Emotion-Detector
   ```
2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
Run the Streamlit application:
```bash
streamlit run app.py
```

## Project Structure
```
Emotion-Detector/
│── app.py                 # Main Streamlit app
│── Logistic_regression.pkl # Pretrained model
│── label_encoder.pkl       # Label encoder
│── tfidf_vectorizer.pkl    # TF-IDF vectorizer
│── requirements.txt        # Dependencies
│── README.md               # Project documentation
```

## Requirements
Ensure you have the following Python libraries installed:
- streamlit
- nltk
- numpy
- pickle
- scikit-learn

## Notes
- If NLTK stopwords cause errors, manually download them using:
  ```python
  import nltk
  nltk.download('stopwords')
  

# Emotion Detector using Text

## Overview
The **Emotion Detector** is a machine learning-based application that predicts emotions (Happy, Sad, or Angry) from a given text input. It utilizes **Natural Language Processing (NLP)** techniques to analyze textual data and classify it into one of the predefined emotions.

## Features
- **Text Preprocessing**: Cleans and prepares the input text using stemming and stopword removal.
- **TF-IDF Vectorization**: Converts text data into numerical features.
- **Machine Learning Model**: A pre-trained Logistic Regression model for emotion classification.
- **User-Friendly Interface**: Built using **Streamlit** for an interactive experience.

## Technologies Used
- **Python**
- **Streamlit** (for the web interface)
- **NLTK** (for text processing)
- **Scikit-learn** (for model training & prediction)
- **NumPy**
- **Regex** (for text cleaning)
- **Pickle** (for model serialization)

## Installation
### Prerequisites
Ensure you have Python installed (Python 3.x recommended). Install required dependencies using:

```bash
pip install -r requirements.txt
```

### Required Libraries
If `requirements.txt` is unavailable, manually install dependencies:

```bash
pip install streamlit nltk numpy scikit-learn pickle-mixin
```

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/Sarthak1500/Emotion_Detector.git
   cd Emotion_Detector
   ```
2. Run the application:
   ```bash
   streamlit run streamlit_app.py
   ```
3. Enter text into the provided input field and click **Predict** to see the detected emotion.

## Model Details
- The model is trained using **Logistic Regression**.
- It is serialized using **Pickle** for easy deployment.
- Uses **TF-IDF Vectorization** for text feature extraction.
- Predicts only three emotions: **Happy, Sad, Angry**.

## Repository
[GitHub Repository](https://github.com/Sarthak1500/Emotion_Detector)

## Future Enhancements
- Expand the emotion categories.
- Improve accuracy with deep learning models.
- Deploy the application online.

## Author
**Sarthak Kushwaha**  
*MCA, MNNIT Allahabad*

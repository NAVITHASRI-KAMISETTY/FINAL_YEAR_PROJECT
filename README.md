# LinkedIn Abuse Detection using Isolation Forests

## Description
This project is an implementation of a LinkedIn post abuse detection system using Isolation Forests. It preprocesses LinkedIn post data, trains an Isolation Forest model, and allows users to classify new messages.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Model Training](#model-training)
- [Prediction](#prediction)
- [Dependencies](#dependencies)
- [License](#license)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/linkedin-abuse-detection.git
## Usage
Ensure you have Python installed.
Install the required dependencies.
Run the Streamlit app:

## streamlit run app.py
Open your browser and navigate to the provided link (usually http://localhost:8501).
Dataset
The dataset used for training is stored in 'linkedin-data.csv'. It contains LinkedIn post data and corresponding labels.

## Preprocessing
The preprocessing step involves cleaning and lemmatizing the text data to prepare it for training.

## Model Training
The project uses an Isolation Forest model for training. The model is trained on the preprocessed data.

## Prediction
After training, the Streamlit app allows users to input a message, and the trained model will classify it as abusive or not.

## Dependencies
pandas
nltk
wordcloud
scikit-learn
streamlit

## Install the dependencies using the following command:

pip install pandas nltk wordcloud scikit-learn streamlit
License
This project is licensed under the MIT License.


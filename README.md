#SMS Spam Classifier

The SMS Spam Classifier is a machine learning-based project that aims to classify text messages as either "spam" or "ham" (not spam).
The project involves data preprocessing, feature extraction, model training, evaluation, and deployment.

##Project Structure
sms-spam-classifier/
│
├── data/
│   ├── spam.csv              # The dataset file containing labeled SMS messages
│
├── notebooks/
│   ├── data_preprocessing.ipynb # Jupyter notebook for data cleaning and preprocessing
│   ├── model_training.ipynb   # Jupyter notebook for model training and evaluation
│
├── src/
│   ├── preprocess.py          # Python script for data preprocessing
│   ├── model.py               # Python script for model training and evaluation
│   ├── classifier.py          # Python script for the trained classifier
│
├── requirements.txt          # Python package dependencies
├── README.md                 # This file
└── app.py                    # Flask app for deploying the classifier as a web service




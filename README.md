# Email-Spam-Detection-using-Naive-Bayes-and-NLP
Welcome to the Email Spam Detection project! This repository provides a complete machine learning pipeline for classifying emails as spam or not spam using Naive Bayes and Natural Language Processing (NLP) techniques.

Overview
This project utilizes the SMS Spam Collection Dataset to train a model that identifies spam emails. It includes:

Data Preprocessing: Tokenization, stopword removal, lemmatization, and feature extraction.
Model Building: Using Naive Bayes classifier for efficient and interpretable spam detection.
Evaluation Metrics: Performance metrics such as accuracy, precision, recall, and F1 score to evaluate the model.
Features
Efficient Text Preprocessing: Includes advanced NLP techniques to clean and prepare data.
Spam Classification: Uses Naive Bayes for classifying emails.
Visualization: Depicts text data trends using Matplotlib.
Installation
Prerequisites
Python 3.7 or later
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Clone the Repository
bash
Copy code
git clone https://github.com/Varshit2448/Email-Spam-Detection-using-Naive-Bayes-and-NLP.git
cd Email-Spam-Detection-using-Naive-Bayes-and-NLP
Usage
Run the preprocessing script to clean the data.
python
Copy code
python preprocess.py
Train the model:
python
Copy code
python train.py
Test with custom inputs:
python
Copy code
python classify.py --input "Your email text here"
Visualizations
Include plots such as word frequency and model evaluation metrics (accuracy, recall, etc.).
Saving the Model
The trained model is saved as a .joblib file for reuse:

python
Copy code
from joblib import dump
dump(model, 'spam_detector.joblib')
Contributing
Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.

License
This project is licensed under the GNU License. See LICENSE for details.

Fake News Detection using Logistic Regression
This repository contains a simple fake news detection project that uses a logistic regression classifier to distinguish between true and fake news articles. The project uses TF-IDF to convert text into numerical features and evaluates the classifier with accuracy and a detailed classification report.

Overview
The project performs the following steps:

Loads and labels datasets for true and fake news.
Cleans the text data by converting it to lowercase and removing non-word characters.
Transforms the cleaned text into numerical features using TF-IDF vectorization.
Splits the data into training and testing sets.
Trains a logistic regression model on the training data.
Evaluates the model on the testing data, printing the accuracy and classification report.
Requirements
Python 3.x
pandas
scikit-learn
numpy
Install the required libraries with:

bash
Copy
Edit
pip install pandas scikit-learn numpy
Folder Structure
graphql
Copy
Edit
fake-news-detection/
├── data/
│   ├── True.csv
│   └── Fake.csv
└── fake_news_detector.py
How to Run
Place the data files (True.csv and Fake.csv) inside the data/ folder.

Open a terminal and navigate to the project directory.

Run the script with:

bash
Copy
Edit
python fake_news_detector.py
The script will process the data, train the model, and output the accuracy and classification report in the console.

Output
The output includes:

Accuracy: The overall percentage of correct predictions.
Classification Report: Detailed metrics (precision, recall, F1-score, and support) for each class (true news labeled as 1 and fake news labeled as 0).

# rule_based_chatbot

I can't directly create a file on your computer or GitHub, but I can give you the complete content for the README.md file. You can simply copy the text below and paste it into a new file on your GitHub repository.

README: ICTHub Chatbot Project
This Jupyter Notebook, chatbot.ipynb, contains a data science project to build a task-oriented chatbot for ICTHub. The project demonstrates the process of building a machine learning-driven chatbot from scratch, including data preprocessing, feature extraction, and model training. The notebook also provides an introductory overview of different types of chatbots, such as Rule-Based, ML-Driven, Generative, and Hybrid models.

Project Overview
The goal of this project is to create a chatbot that can understand user queries and provide appropriate, predefined responses. The chatbot is trained on a labeled dataset of user inputs and their corresponding categories and responses. The notebook uses a Logistic Regression model to classify user input and predict the correct response.

Dependencies
The following Python libraries are required to run this notebook:

numpy

pandas

matplotlib

seaborn

scikit-learn

nltk

string

difflib

random

Dataset
The project uses an Excel file named icthub_dataset.xlsx. The dataset contains 715 entries and includes the following columns:

User Input: The raw text entered by the user.

Category: The intent or category of the user's input.

Chatbot Response: The predefined response for the given category.

Methodology
The notebook follows a machine learning workflow to build the chatbot:

Data Cleaning: Duplicate entries are removed from the dataset, reducing the count from 715 to 713. The dataset is checked for missing values, and none are found.

Preprocessing: A custom function is used to preprocess the User Input text. This process includes:

Converting text to lowercase

Tokenizing the text

Removing special characters, stopwords, and punctuation

Applying stemming to words

Vectorization: The preprocessed text data is converted into numerical features using the TfidfVectorizer from scikit-learn.

Model Training: The data is split into a training set and a testing set. A Logistic Regression model is trained on the vectorized training data to predict the Category of a user's input.

Model Evaluation: The performance of the model is evaluated using a classification report, and its accuracy is calculated to measure how well it predicts the correct category for new user inputs.

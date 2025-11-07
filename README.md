# Fake-News-Detection-Model

📰 Fake News Detection System

Group 10: Shreya Singhal, Aryan Mittal, Samyak Bansal
Topic: Fake News Detection — Minimizing User Exposure to
Misleading Content

1. About The Project

This project is a machine learning system designed to classify news articles as "Real" or "Fake." It uses a Logistic Regression model trained on a large dataset of news articles. The system processes raw text, extracts features using TF-IDF, and makes a prediction.

The project includes:

A Jupyter Notebook (Fake_News_Detection.ipynb) detailing the entire process from data cleaning and Exploratory Data Analysis (EDA) to model training and evaluation.

An interactive demo within the notebook that allows users to paste in their own text and get a live classification.

Model interpretability using LIME to explain why the model classified an article as real or fake.

2. Tech Stack

Backend: Python

Data Science: Pandas, NumPy, Scikit-learn (for TF-IDF & Logistic Regression)

NLP: NLTK

Demo: Streamlit (run within the notebook)

Model Interpretability: LIME

3. How to Run This Project

You can run this project either in Google Colab or on your local machine.

Option A: Run in Google Colab (Recommended)

This is the fastest way to get started.

Open in Colab:

Go to Google Colab.

Select File > Upload notebook and upload the Fake_News_Detection.ipynb file.

Upload Data:

In the Colab file browser (folder icon on the left), click the "Upload" button.

Upload your dataset file: archive (1).zip.

Upload the requirements file: requirements.txt.

Install Dependencies:

In a new code cell, run the following command to install all required libraries:

!pip install -r requirements.txt


Run the Notebook:

Run all the cells in the notebook from top to bottom. The notebook will load the data, train the model, and run the final demo.


4. Project File Structure

├── dataset/              # Data (ignored by git, must be downloaded)
├── .gitignore            # Tells git which files to ignore
├── Fake_News_Detection.ipynb # The main notebook with all analysis, training, and demo
├── requirements.txt      # List of Python dependencies


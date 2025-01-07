# Human-Activity-Classification-
Project Overview
This project aims to classify human activities using data collected from smartphone sensors (accelerometer and gyroscope). The dataset comprises labeled activity data from 30 individuals performing various activities, both static and dynamic.

Training data : https://drive.google.com/file/d/1F9aujfGr_KEdAKiahquDia-6Owp7h9q_/view?usp=sharing
Test data : https://drive.google.com/file/d/1tBkbeFVxy3UGJWoqfRwK0XQR7NNZsbQj/view?usp=sharing
The key goal is to design, train, and evaluate machine learning models, including Random Forest, XGBoost, and additional methods, to achieve high accuracy in activity recognition.

Key Objectives
Gain hands-on experience in the practical application of machine learning for human activity recognition.
Explore, preprocess, and analyze sensor data.
Train multiple machine learning models and evaluate their performance.
Dataset Details
The dataset is derived from smartphone sensors (Samsung Galaxy S II) and includes the following:

Activities: 12 activity classes, including walking, standing, sitting, and transitional movements.
Features: 561 variables extracted using time-domain and frequency-domain transformations.
Data Files
activity_train.csv: Contains the training data with 561 features and labeled activity classes.
activity_test.csv: Contains the test data for evaluation.
features_info.txt: Provides detailed descriptions of the features.
Feature Engineering
Raw accelerometer and gyroscope signals processed using filters to remove noise.
Time-domain features (tBodyAcc, tGravityAcc, etc.) and frequency-domain features (fBodyAcc, fBodyGyro, etc.) are extracted.
Statistical and signal processing features include:
Mean
Standard deviation
Energy
Skewness
Kurtosis
Fast Fourier Transform (FFT) outputs
Activities
The dataset includes the following activities:

Walking
Walking Upstairs
Walking Downstairs
Sitting
Standing
Laying
Transition movements (e.g., Stand-to-Sit, Sit-to-Stand)
Project Workflow
Data Loading: Import the training and testing datasets.
Exploratory Data Analysis (EDA): Explore the dataset for patterns, distributions, and feature correlations.
Preprocessing: Clean and normalize data for consistent inputs to the models.
Model Training: Train machine learning models, including:
Random Forest
XGBoost
Additional custom models (e.g., [Add your methods here])
Model Evaluation:
Use test data to evaluate accuracy, F1-score, and other metrics.
Analyze errors and fine-tune hyperparameters for optimal performance.
Results
Summary of model performances, with tables or plots comparing accuracy, precision, recall, and F1-scores.
Highlighted feature importance and insights from the dataset.
Setup Instructions
Clone the repository:
bash
Copy code
git clone https://github.com/abdelrhmanibrahim00/Human-Activity-Recognition-
Navigate to the project directory:
bash
Copy code
cd Human-Activity-Recognition-
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Run the Jupyter Notebook for training and evaluation:
bash
Copy code
jupyter notebook Human_Activity_Recognation.ipynb
Conclusion
This project provides a comprehensive workflow for building a machine learning solution for activity recognition. It demonstrates:

Effective preprocessing and feature engineering.
Training and evaluation of multiple machine learning models.
Insights from dataset exploration and model performance.

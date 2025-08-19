# AI_in_Education_Field_feedback_system

# Personalized Learning AI Model

This AI model aims to provide personalized learning experiences by incorporating sentiment analysis and facial expression recognition to analyze student emotions during courses.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Model Architecture](#model-architecture)
- [Setup](#setup)
- [Dataset](#dataset)
- [Training](#training)
- [Evaluation](#evaluation)
- [Troubleshooting](#troubleshooting)
- [License](#license)



## Introduction

This repository contains an emotion detection project that integrates sentiment analysis from text feedback and facial expression recognition using DeepFace. The goal is to analyze user feedback using text sentiment classification and validate it with facial emotion recognition.

## Features

Text sentiment analysis using Logistic Regression with TF-IDF vectorization

Facial emotion recognition using DeepFace

Custom stop words filtering for text preprocessing

Hyperparameter tuning using GridSearchCV

Stratified K-Fold cross-validation for model evaluation

Preprocessing steps including tokenization and text cleaning using regex

## Model Architecture

Text Sentiment Analysis: Uses Logistic Regression with TF-IDF vectorization for feature extraction.

Facial Emotion Recognition: Utilizes DeepFace for analyzing facial expressions.

Fusion Strategy: Combines results from both text and face analysis to provide a holistic emotional assessment.

## Setup

Clone the repository:

git clone https://github.com/LavanyaSrinivas06/AI_in_Education_Field_feedback_system.git
cd AI_in_Education_Field_feedback_system

Install the required dependencies:

pip install -r requirement.txt

## Dataset

text_feedback_dataset.csv: Contains text feedback samples labeled for sentiment analysis.

stop_words_list.py: Contains custom stop words for filtering.

Image dataset for facial emotion recognition processed with OpenCV.

## Training
   
   Train the text sentiment analysis model using Logistic Regression.
   Fine-tune hyperparameters using GridSearchCV.
   Train the facial emotion recognition model using DeepFace.

## Evaluation

   Evaluate text-based sentiment analysis using accuracy scores and classification reports.
   Assess facial emotion recognition performance using DeepFace metrics.
   Compare results from both models to detect inconsistencies in feedback.

   <img width="2078" height="1164" alt="image" src="https://github.com/user-attachments/assets/42dc97e0-d272-460e-91ad-bf283538ab92" />


## Troubleshooting

   Installation Issues: Ensure all dependencies are installed properly using pip install -r requirements.txt.
   Model Performance: If the model performs poorly, try tuning hyperparameters or increasing dataset size.
   Data Preprocessing: Check if stop words filtering and tokenization are correctly applied.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


## Authors

Lavanya Srinivas
Ruchitha Prakash
Tanisqha Venkataram




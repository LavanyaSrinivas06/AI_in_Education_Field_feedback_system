# AI in Education Field Feedback System
## Personalized Learning AI Model


This AI model aims to provide personalized learning experiences by incorporating sentiment analysis and facial expression recognition to analyze student emotions during courses.

## 📑 Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Model Architecture](#model-architecture)
- [Setup](#setup)
- [Dataset](#dataset)
- [Training](#training)
- [Evaluation](#evaluation)
- [Troubleshooting](#troubleshooting)
- [License](#license)
- [Authors](#authors)



## Introduction

This repository contains an **emotion detection project** that integrates:
- **Text sentiment analysis** (Logistic Regression + TF-IDF)
- **Facial emotion recognition** (DeepFace + OpenCV)

## Features

- Text sentiment analysis using Logistic Regression with TF-IDF  
- Facial emotion recognition using DeepFace  
- Custom stop words filtering for text preprocessing  
- Hyperparameter tuning with GridSearchCV  
- Stratified K-Fold cross-validation  
- Fusion strategy combining text + face analysis

## Model Architecture

- **Text Sentiment Analysis** → Logistic Regression + TF-IDF vectorization  
- **Facial Emotion Recognition** → DeepFace-based classifier  
- **Fusion Strategy** → Combines both results for robust feedback insights 

![Architecture Diagram]<img width="1667" height="1164" alt="image" src="https://github.com/user-attachments/assets/66e055b3-23be-48f1-bad7-5c6d8163fd1b" />


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
   
Train the text sentiment analysis model (Logistic Regression).
Fine-tune hyperparameters via GridSearchCV.
Train the facial emotion recognition model (DeepFace).

## Evaluation

   Evaluate text-based sentiment analysis using accuracy scores and classification reports.
   Assess facial emotion recognition performance using DeepFace metrics.
   Compare results from both models to detect inconsistencies in feedback.
<p align="center">
  <img src="https://github.com/user-attachments/assets/c8b4f490-dd44-4391-b905-b329fabbc96e" width="220" />
  <img src="https://github.com/user-attachments/assets/02949551-b68a-40ae-b4f3-6a06059dada0" width="220" />
  <img src="https://github.com/user-attachments/assets/d01c6536-cb8c-417e-87c4-e74bb24009ee" width="220" />
  <img src="https://github.com/user-attachments/assets/af6d1b90-972a-47bf-b29a-216611253b91" width="220" />
</p>




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






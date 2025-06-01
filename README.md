# SMS Spam Detection

This project implements a machine learning-based SMS spam detection system using Python and popular ML libraries. The system classifies SMS messages into **spam** or **ham (non-spam)** categories.

---

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Model Performance](#model-performance)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

This project uses natural language processing (NLP) techniques and machine learning classifiers to detect spam messages in SMS text. It preprocesses the text data, converts messages to TF-IDF features, and applies multiple classification models including:

- Naive Bayes
- Logistic Regression
- Support Vector Machine (SVM)

The model performance is evaluated with accuracy scores and classification reports.

---

## Dataset

The dataset used is the [SMS Spam Collection Dataset](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection), which contains 5,574 SMS messages labeled as "ham" (legitimate) or "spam".

---

## Features

- Text cleaning and preprocessing (removes punctuation, converts to lowercase, removes numbers)
- TF-IDF vectorization of SMS messages
- Model training and evaluation with Naive Bayes, Logistic Regression, and SVM
- Accuracy and detailed classification reports for each model

---

## Technologies Used

- Python 3.x
- Pandas
- Scikit-learn
- Regex
- Jupyter Notebook (optional)

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/lakkireddyaditya/CODSOFT.git
   cd CODSOFT

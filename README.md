# Suicide_Detection

## Overview

This project aims to detect suicidal ideation in text using machine learning techniques. It leverages Natural Language Processing (NLP) and classification algorithms to classify text into either suicidal or non-suicidal categories.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)

## Introduction

In recent years, mental health awareness has become increasingly important, with efforts directed towards early detection and intervention for individuals at risk. One critical aspect of this is identifying suicidal ideation, which can often be expressed through textual communication, such as social media posts, forum discussions, or even personal messages.

The Suicide Detection Project is an initiative aimed at leveraging machine learning techniques to automatically detect signs of suicidal thoughts in textual data. By analyzing the language and content of text, the project seeks to identify patterns and indicators that may suggest the presence of suicidal ideation.

Using a dataset containing textual samples labeled as either suicidal or non-suicidal, the project trains machine learning models to classify new text inputs into these categories. The ultimate goal is to develop a tool that can assist mental health professionals, social media platforms, and other stakeholders in identifying individuals who may be at risk of self-harm or suicide, allowing for timely intervention and support.

This README provides an overview of the project, including details on the dataset used, instructions for running the code, the directory structure of the repository, contributions from collaborators, and licensing information.
## Features

- Utilizes sentiment analysis for text classification.
- Integration with popular machine learning libraries such as TensorFlow and Keras.
- Evaluation metrics for assessing the model's performance.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/AmineRaouane/Suicide_Detection.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```


## Dataset

The project utilizes a curated dataset that is a collection of posts from the "SuicideWatch" and "depression" subreddits of the Reddit platform.. The dataset is obtained from [source link](https://www.kaggle.com/datasets/nikhileswarkomati/suicide-watch).

## Preprocessing

The preprocessing script encode the text column to use it in the modeling part.

## Model Training

The model is trained on the preprocessed dataset using the TensorFlow and Keras libraries. Hyperparameters can be adjusted in the `Suicide.ipynb` script.

## Evaluation

The model's performance is evaluated using metrics such as accuracy, precision, recall, and F1 score. These metrics provide insights into the model's ability to correctly classify suicidal and non-suicidal texts.

## Results

Upon training and evaluation, the project provides insights into the model's performance. Results, including confusion matrices and classification reports, are presented in the `Suicide.ipynb` script.

## Contributing

Contributions to the project are welcome. Feel free to open issues, propose new features, or submit pull requests.


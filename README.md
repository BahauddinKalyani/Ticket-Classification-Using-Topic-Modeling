# Ticket-Classification-Using-Topic-Modeling

This project aims to streamline the process of categorizing complaint tickets by utilizing a combination of topic modeling and classification techniques. The primary goal is to identify the most relevant topics within the tickets and subsequently classify them into appropriate categories. In this project, we employ Non-Negative Matrix Factorization (NMF) for topic modeling and evaluate classification models including Multinomial Naive Bayes, Logistic Regression, Decision Tree Classifier, and Random Forest Classifier.

## Notebook Description

This notebook provides an in-depth exploration of the complaint ticket dataset using Non-Negative Matrix Factorization (NMF). NMF is employed to uncover latent topics within the text data, revealing underlying patterns and structures. The notebook guides you through the process of preprocessing the text, creating a term-document matrix, applying NMF, and visualizing the discovered topics. Later, we delve into the world of classification models for the task of assigning complaint tickets to relevant categories. Multinomial Naive Bayes, Logistic Regression, Decision Tree Classifier, and Random Forest Classifier are evaluated and compared. The notebook covers data preprocessing, feature extraction, model training, hyperparameter tuning, and comprehensive model evaluation.

- Perform topic modeling using NMF to extract underlying topics from complaint tickets.
- Utilize classification models to assign relevant categories to the complaint tickets.
- Evaluate model performance based on various evaluation metrics.
- Identify the best-performing classification model for the task.

## Contents

- [Notebook](ticket-classification-using-topic-modeling.ipynb): Jupyter Notebook containing the analysis.
- [Data](data/complaints-2021-05-14_08_16.json): Sample dataset used for the analysis.
- [README.md](README.md): This file, providing an overview of the repository.


## Usage

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/BahauddinKalyani/Ticket-Classification-Using-Topic-Modeling.git

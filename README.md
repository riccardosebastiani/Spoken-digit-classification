# Spoken-digit-classification
A straightforward python coded algorithm useful for spoken digit classification

## Overview
The aim of this project is to develop and evaluate a machine learning model for audio classification tasks, with a focus on speech recognition. The code begins by preparing the dataset and extracting the necessary target labels for supervised learning. It then computes Mel-frequency cepstral coefficients (MFCCs) to capture essential audio characteristics. Utilizing K-Fold cross-validation, it evaluates multiple algorithms to determine the most suitable one. After splitting the data into training and testing subsets, it conducts a randomized search to optimize hyperparameters for improved model performance.

Subsequently, the code trains a Random Forest classifier, an ensemble learning method, on the training data. Finally, it evaluates the trained model on the testing data, reporting key performance metrics such as accuracy, precision, recall, and F1-score to assess its effectiveness in classification tasks.

## Dataset
The dataset used in this project is the Free Spoken Digit Dataset, consisting of recordings of spoken digits from 0 to 9. It contains a total of 3000 audio files.

## Dataset Attribution
The dataset used in this project was obtained from [Jakobovski/free-spoken-digit-dataset](https://github.com/Jakobovski/free-spoken-digit-dataset) and is released under the [Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/). It is important to note that:

- The dataset is subject to the terms of the license; please refer to the license for further information on its usage.
- Please provide appropriate credit to the licensor when using the dataset.

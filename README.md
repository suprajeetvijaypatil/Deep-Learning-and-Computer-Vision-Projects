# Deep-Learning-and-Computer-Vision-Projects
This repository contains advanced projects focusing on model robustness, temporal data prediction, and semantic text analysis using deep learning architectures.

# Deep Neural Networks & Pattern Recognition Portfolio
**Student:** SUPRAJEET VIJAY PATIL 
**Institution:** Hochschule Heidelberg 
**Date:** January 2026

This portfolio showcases technical implementations in security analysis, adversarial robustness, temporal forecasting, and natural language processing.

---

## 📁 Projects Overview

### 1. Dictionary Attack against a Spam Filter
* **Objective:** Evaluate the vulnerability of automated spam filters by implementing a dictionary-based attack to bypass classification logic.
* **Methodology:** Developed a Python script to perform "word-mapping," utilizing legitimate vocabulary to mask spam content.
* **Key Insight:** Demonstrates that statistical classifiers can be subverted by exploiting their underlying logic through intentional semantic masking.

### 2. Adversarial Attacks (PGD) on MNIST
* **Objective:** Explore the robustness of deep learning models against intentional, human-imperceptible perturbations.
* **Methodology:** Implemented the **Projected Gradient Descent (PGD)** attack, an iterative method for finding adversarial examples within a specific $\epsilon$-ball constraint.
* **Analysis:** Evaluated how a Convolutional Neural Network's performance degrades when faced with white-box adversarial pressure.

### 3. Time Series Forecasting (TOTALSA)
* **Objective:** Predict future economic indicators using historical seasonally adjusted data.
* **Dataset:** Utilized the `TOTALSA.csv` dataset, representing Total Seasonally Adjusted sales data.
* **Technical Implementation:**
    * **Data Preprocessing:** Applied normalization and a sliding window approach to prepare time-ordered sequences.
    * **Architecture:** Developed and trained a recurrent model (RNN/LSTM) to minimize Mean Squared Error (MSE) in future value predictions.

### 4. Word Embeddings & News Classification
* **Objective:** Categorize news articles based on semantic meaning using Natural Language Processing (NLP).
* **Methodology:**
    * **Word Embeddings:** Implemented dense vector representations to capture semantic relationships between words.
    * **Classification:** Designed a Deep Neural Network to classify news text into distinct categories.
* **Analysis:** Investigated how high-dimensional vector spaces improve the accuracy of text-based classification models.

---

## 🛠️ Technical Stack
* **Programming:** Python 
* **Libraries:** TensorFlow, Keras, PyTorch, OpenCV (cv2), NumPy, Pandas, Matplotlib. 
* **Platform:** Google Colab. 

## 🎓 Academic Context
* **Course:** Deep Neural Networks / Pattern Recognition.
* **Faculty:** Professor Gnjatovic.






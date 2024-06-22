# Mini-Project for Fundamentals of Machine Learning Course
![background](./materials/ai_wp.jpg)
This repository contains the code and data for a mini-project on facial expression recognition using machine learning algorithms.

## 📑 Project Policy
- Team: group should consist of 3-4 students.

    |No.| Student Name    | Student ID |
    | --------| -------- | ------- |
    |1|Nguyễn Trọng Nhân|21280038|
    |2|Bùi Minh Huy|21110306|
    |3|Nguyễn Tấn Tài|21110386|
    |4|Phạm Tấn Tài|21110388|

- The submission deadline is strict: **11:59 PM** on **June 22nd, 2024**. Commits pushed after this deadline will not be considered.

## 📦 Project Structure

The repository is organized into the following directories:

- **/data**: This directory contains the facial expression dataset. You'll need to download the dataset and place it here before running the notebooks. (Download link provided below)
- **/notebooks**: This directory contains the Jupyter notebook ```EDA.ipynb```. This notebook guides you through exploratory data analysis (EDA) and classification tasks.

## Model Evaluation and Results

**Original Data**:
- **Random Forest**:
	- Accuracy: 0.37
	- F1-score: 0.24
	- Precision-score: 0.37
	- Recall: 0.37
- **SVC**:
	- Accuracy: 0.31
	- F1-score: 0.24
	- Precision-score: 0.34
	- Recall: 0.31
- **Logistic Regression**:
	- Accuracy: 0.33
	- F1-score: 0.32
	- Precision-score: 0.31
	- Recall: 0.33
- **MLP Classifier**:
	- Accuracy: 0.37
	- F1-score: 0.31
	- Precision-score: 0.37
	- Recall: 0.37

**PCA Data**:
- **Random Forest**:
	- Accuracy: 0.31
	- F1-score: 0.14
	- Precision-score: 0.40
	- Recall: 0.31
- **SVC**:
	- Accuracy: 0.31
	- F1-score: 0.20
	- Precision-score: 0.34
	- Recall: 0.31
- **Logistic Regression**:
	- Accuracy: 0.36
	- F1-score: 0.27
	- Precision-score: 0.33
	- Recall: 0.36
- **MLP Classifier**:
	- Accuracy: 0.35
	- F1-score: 0.31
	- Precision-score: 0.35
	- Recall: 0.35

Among all the models, **MLP (Multilayer Perceptron)** appears to be the top performer across both original and PCA-transformed datasets.

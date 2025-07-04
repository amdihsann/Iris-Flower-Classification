# Iris Flower Classification: A Comparative Analysis of SVM and KNN Models

## Project Overview

This project focuses on the accurate classification of Iris flowers into their three distinct species (*Iris Setosa*, *Iris Versicolor*, and *Iris Virginica*) based on their morphological measurements. Utilizing the renowned scikit-learn Iris dataset, a classic benchmark in machine learning, this endeavor serves as an excellent practical exercise for understanding fundamental classification concepts.

A comparative analysis was conducted between two prominent classification algorithms: **Support Vector Machine (SVM)** and **K-Nearest Neighbors (KNN)**. The goal was to evaluate their performance, decision-making processes, and suitability for this specific classification task.

## Project Pipeline

The project followed a systematic machine learning pipeline:

* **Data Acquisition & EDA:** <br> The Iris dataset was loaded, and an initial exploration was performed to understand its characteristics, including class distribution and basic statistics.
* **Feature Selection & Preprocessing:** <br> Key features (petal length & petal width) were identified based on exploratory analysis. The data was then split into training and testing sets, and features were standardized.
* **Model Building & Evaluation:** <br> Both Support Vector Machine (SVM) and K-Nearest Neighbors (KNN) classifiers were developed, trained, and rigorously evaluated.
* **Comparative Analysis:** <br> A detailed comparison of SVM and KNN performance, including their strengths and suitability for the classification problem, was conducted.

## Exploratory Data Analysis (EDA) Insights

Exploratory Data Analysis revealed critical insights into the Iris dataset's structure and feature relationships:

* **Balanced Dataset:** <br> The Iris dataset features a perfectly balanced class distribution (50 samples per species), ensuring unbiased classification.
   

* **Feature Distributions:** <br> Distinct feature distributions, especially in petal length and width, clearly separate species, with Setosa being notably smaller.


* **Feature Relationships & Correlation:**<br> The combination of petal length and petal width is highly effective in visually separating all three Iris species. This was supported by high positive correlation (0.96) between these features and the target variable.



## Model Performance and Comparative Analysis

Both Support Vector Machine (SVM) and K-Nearest Neighbors (KNN) models demonstrated exceptional performance in classifying Iris species, achieving **100% accuracy on the test set**. This outstanding result is attributed to the dataset's clear class separability and the effective selection of petal features.

| Model | Training Accuracy | Test Accuracy | Mean Cross-Validation Accuracy |
| :---- | :---------------- | :------------ | :----------------------------- |
| SVM   | `0.94` | `[1.00]` | `[0.94]` |
| KNN   | `[0.96]` | `[1.00]` | `[0.95]` |


* **SVM's Strengths:** The SVM model excels in creating smooth, robust decision boundaries and shows strong generalization across cross-validation.

* **KNN's Strengths & Considerations:** KNN, while simpler, is highly adaptable to data complexities; `k=5` performed optimally for this dataset.

* **Overall Reliability:** Neither model exhibited overfitting or underfitting, indicating highly reliable and trustworthy predictions for the Iris classification.

## Key Takeaways

* The Iris dataset serves as an excellent benchmark for classification tasks due to its clear class separability.
* `Petal length` and `petal width` are highly discriminative features, crucial for accurate Iris species differentiation.
* Both SVM (with RBF kernel) and KNN (with an optimal `k` value) are highly effective and reliable classifiers for this type of data.

## Connect with Me

I'm always eager to discuss new ideas, potential collaborations, or exciting opportunities in the field of Machine Learning. Please feel free to connect!

* **Email:** ahmadihsan506@gmail.com
* **GitHub:** https://github.com/amdihsann 
* **LinkedIn:** https://www.linkedin.com/in/ahmadihsan-/ 

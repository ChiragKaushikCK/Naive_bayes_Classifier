# Naive_bayes_Classifier

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-learn" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter" />
</div>

<h1 align="center">
  <br>
  <a href="https://github.com/your-username/naive-bayes-classifier"><img src="https://raw.githubusercontent.com/Anandp711/Weather-prediction-using-multiple-models/main/Assets/images/header.png" alt="Naive Bayes Classifier" width="600"></a>
  <br>
  Naive Bayes Classifier for Social Network Ads Prediction 🎯
  <br>
</h1>

<div align="center">
  <p>
    An implementation of the Gaussian Naive Bayes classification algorithm to predict user purchasing behavior based on social network ad data.
  </p>
</div>

<br>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#features">Features</a></li>
    <li><a href="#dataset">Dataset</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#model-performance">Model Performance</a></li>
    <li><a href="#contributing">Contributing</a></li>
  </ol>
</details>

---

## <a id="about-the-project"></a> 📚 About The Project

This project demonstrates the application of the **Gaussian Naive Bayes** algorithm for a classification task. The goal is to predict whether a user will purchase a product based on their interaction with social network advertisements. The notebook covers essential steps in a machine learning workflow, including data loading, preprocessing, model training, prediction, and evaluation.

---

## <a id="features"></a> ✨ Features

* **Data Loading & Initial Inspection**: Loads the `Social_Network_Ads.csv` dataset and performs basic checks.
* **Feature and Target Separation**: Clearly distinguishes independent variables (features) from the dependent variable (target).
* **Data Splitting**: Divides the dataset into training and testing sets to ensure robust model evaluation.
* **Feature Scaling**: Applies `StandardScaler` to normalize numerical features, which is crucial for distance-based algorithms and can improve the performance of many machine learning models.
* **Gaussian Naive Bayes Implementation**: Trains a Gaussian Naive Bayes classifier on the preprocessed data.
* **Prediction and Evaluation**: Generates predictions on the test set and evaluates the model's performance using a confusion matrix and accuracy score.

---

## <a id="dataset"></a> 📊 Dataset

The dataset used in this project is `Social_Network_Ads.csv`. It typically contains information about users, including their age, estimated salary, and whether they purchased a particular product after seeing a social network ad.

**Columns:**
* `Age`
* `EstimatedSalary`
* `Purchased` (Target Variable: 0 for No, 1 for Yes)

---

📈 Model Performance
After training and evaluating the Gaussian Naive Bayes model on the test set, the following performance metrics were observed:

Accuracy Score: The model achieved an accuracy of approximately 90.0%.

Confusion Matrix:

[[65  3]
 [ 5 27]]

# 📧 Spam Detection, Feature Analysis & Anomaly Detection

This repository contains a **machine learning pipeline** for **spam classification, feature importance analysis, and anomaly detection** using the **Spambase dataset**.

## 🚀 Features:

- **Spam Classification** using **Logistic Regression, Random Forest, SVM, and Neural Networks**.
- **Feature Importance Analysis** using **SHAP values** to explain model decisions.
- **Anomaly Detection** using **K-Means Clustering and Autoencoders** to detect suspicious email patterns.
- **Data Preprocessing** with **StandardScaler & PCA** for dimensionality reduction.
- **Visualization** of feature importance and clustering results.

## 📌 Installation & Setup

### 1️⃣ **Clone the Repository**

```bash
git clone https://github.com/yourusername/spam-detection-ml.git
cd spam-detection-ml
```

### 2️⃣ **Install Dependencies**

Ensure you have Python installed, then install the required libraries:

```bash
pip install -r requirements.txt
```

### 3️⃣ **Run the Jupyter Notebook**

```bash
jupyter notebook
```

Open `spam_detection_ml.ipynb` and execute the cells.

## 🛠 Usage Guide

### 🔍 **1. Train Spam Detection Models**

- The notebook automatically **splits the data**, **trains models**, and **evaluates accuracy**.
- The following classifiers are included:
  - ✅ Logistic Regression
  - ✅ Random Forest
  - ✅ Support Vector Machine (SVM)
  - ✅ Neural Network (MLPClassifier)

### 📊 **2. Analyze Feature Importance**

- The model utilizes **SHAP values** to show which words and patterns contribute most to classification.
- Run the SHAP section to generate visualizations.

### 🚨 **3. Detect Anomalies**

- **K-Means Clustering** is applied to identify outliers in email patterns.
- **Autoencoders** are used to reconstruct normal email patterns and detect anomalies.
- The results are plotted for easy analysis.

## 📷 Sample Outputs:

- **Spam Classification Accuracy**
  ```
  Random Forest Accuracy: 97.4%
  ```
- **Feature Importance (SHAP Summary Plot)**\

- **K-Means Clustering Visualization**\

- **Autoencoder Reconstruction Error**\


## 🤝 Contributing

Feel free to **fork** this repository, submit **issues**, and create **pull requests** to improve the model!

---

🚀 **Happy Coding!** 🚀

